---
title: "Comment connecter une base de données Public Cloud Databases avec un hébergement web OVHcloud"
excerpt: "Découvrez comment connecter une base de données Public Cloud Databases avec votre hébergement web OVHcloud"
updated: 2025-02-17
---

## Objectif

Les bases de données Public Cloud Databases d'OVHcloud offrent une solution managée performante pour vos applications web. Pour qu'un site web hébergé sur un hébergement mutualisé, un VPS ou un serveur dédié puisse communiquer avec une base de données Public Cloud Databases, il est nécessaire d'effectuer certaines configurations. Ce guide vous explique pas à pas comment connecter votre hébergement web OVHcloud à une base de données Public Cloud Databases.

**Découvrez comment connecter une base de données Public Cloud Databases avec votre hébergement web OVHcloud.**

## Prérequis

- Disposer d'une offre d'[hébergement web OVHcloud](/links/web/hosting)
- Un [projet Public Cloud](/links/public-cloud/public-cloud) dans votre compte OVHcloud
- Une base de données fonctionnant sur votre Public Cloud Databases
- Être connecté à votre [espace client OVHcloud](/links/manager)

## En pratique

### Autoriser l'accès à votre base de données Public Cloud Databases

#### Identifier l’adresse IP de votre hébergement web OVHcloud

Pour retrouver l'adresse IP de votre hébergement web, connectez-vous à votre [espace client OVHcloud](/links/manager), puis rendez-vous dans la partie `Web Cloud`{.action} situé en haut de la page. Cliquez sur l'onglet `Hébergements`{.action} dans la colonne de gauche, puis sélectionnez l'hébergement web concerné dans la liste. Identifiez l'adresse `IPv4` dans l'encadré `Informations générales`{.action} et conservez-la pour l'étape suivante.

#### Autoriser l'adresse IP de votre hébergement web

Dans votre [espace client OVHcloud](/links/manager), rendez-vous dans la partie `Public Cloud`{.action} pour effectuer les actions suivantes :

- Cliquez sur `Databases`{.action} dans la barre de navigation de gauche et sélectionnez votre instance.
- Rendez-vous dans l'onglet `Configuration`{.action}.
- Identifiez la section  `IPs`{.action}, cliquez sur l'icône représentant un `+`{.action} et ajoutez l'adresse IP de votre hébergement web.

### Récupérer les informations de connexion à la base de données

Une fois l'adresse IP de votre hébergement web ajoutée et validée, récupérez les informations nécessaires pour établir la connexion :

- **Hôte (Host)** : Adresse de la base de données.
- **Port** : Numéro de port à utiliser pour la connexion.
- **Nom d'utilisateur** : Identifiant du compte autorisé à se connecter.
- **Mot de passe** : Mot de passe associé à l'utilisateur.
- **Nom de la base de données** : Nom de la base de données à laquelle vous souhaitez accéder.

Pour récupérer l'hôte et le port, cliquez sur l'instance de votre base de données Public Cloud Databases puis dirigez-vous dans l'onglet `Dashboard`{.action}. Trouvez les informations d'hôte et de port dans la section `Informations de connexion`{.action}.

![connectwhpcdb](/pages/web_cloud/web_hosting/connect_pcdb_web_hosting/images/PCDB_connexion_information.png){.thumbnail}

Pour récupérer le nom d'utilisateur, dirigez-vous dans l'onglet `Utilisateurs`{.action} et identifiez l'utilisateur que vous souhaitez utiliser pour la connexion ainsi que le mot de passe associé.

Pour récupérer le nom de la base de données, dirigez-vous dans l'onglet `Base de données`{.action} pour choisir celle que vous souhaitez utiliser pour la connexion.

### Configurer votre site web pour se connecter à la base de données

#### Modifier le fichier de configuration de votre site web

1. Accédez à votre hébergement web via FTP ou le gestionnaire de fichiers. Ouvrez le fichier de configuration et modifiez les lignes suivantes :

> [!tabs]
> WordPress
>> ```php
>> define('DB_NAME', 'nom_base_de_donnees');
>> define('DB_USER', 'nom_utilisateur');
>> define('DB_PASSWORD', 'mot_de_passe_utilisateur');
>> define('DB_HOST', 'hote:port');
>> ```
> Joomla
>> ```php
>> public $db = 'nom_base_de_donnees';
>> public $user = 'nom_utilisateur';
>> public $password = 'mot_de_passe_utilisateur';
>> public $host = 'hote:port';
>> ```
> Drupal
>> ```php
>> $databases['default']['default'] = array (
>> 'database' => 'nom_base_de_donnees',
>> 'username' => 'nom_utilisateur',
>> 'password' => 'mot_de_passe_utilisateur',
>> 'host' => 'hote',
>> 'port' => 'port')
>> ```
> Prestashop
>> ```php
>> 'database_host' => 'hote',
>> 'database_port' => 'port',
>> 'database_name' => 'nom_base_de_donnees',
>> 'database_user' => 'nom_utilisateur',
>> 'database_password' => 'mot_de_passe_utilisateur',
>> ```

### Tester la connexion

Après avoir configuré votre site web, effectuez un test de connexion :

- **Depuis votre site web** : Vérifiez si l'application peut récupérer des informations depuis la base de données Public Cloud Databases.
- **Dans les logs** : Consultez les fichiers de logs de votre hébergement pour identifier d'éventuelles erreurs.

Si vous rencontrez des problèmes, assurez-vous que :

- L'adresse IP de votre hébergement est bien autorisée dans la configuration de la base de données Public Cloud Databases.
- Les informations renseignées dans le fichier de configuration de votre hébergement web sont correctes.
- Aucune règle de pare-feu ne bloque la connexion.

## Aller plus loin <a name="go-further"></a>

Pour des prestations spécialisées (référencement, développement, etc.), contactez les [partenaires OVHcloud](/links/partner).

Échangez avec notre [communauté d'utilisateurs](/links/community).