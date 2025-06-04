---
title: 'User roles and permissions in Hosted Private Cloud'
excerpt: 'Explore which actions are allowed for Administrator, Contributor, and Read-only roles across Hosted Private Cloud services.'
updated: 2025-06-03
---

## Objective

**This guide provides an exhaustive breakdown of what each user role can do across the Hosted Private Cloud platform.**

Use the table of contents below to jump directly to the category you’re interested in.

## Permissions overview

Click below to explore permissions by category:

- [Virtual Machines (vSphere)](#virtual-machines-vsphere)
- [Networking (NSX, vSphere)](#networking-nsx-vsphere)
- [Storage & Datastores](#storage--datastores)
- [vApp & Guest operations](#vapp--guest-operations)
- [Backup & Restore](#backup--restore)
- [Tagging](#tagging)
- [Lifecycle Management](#lifecycle-management)
- [Alarms](#alarms)
- [Folders & Resources](#folders--resources)
- [Advanced & Internal Operations](#advanced--internal-operations)

## Virtual Machines (vSphere)

This section covers core VM operations, configuration changes, lifecycle management, and snapshot handling in vSphere.

### VM lifecycle and configuration

| Action | Administrator | Contributor | Read-only |
|--------|---------------|-------------|-----------|
| Create and delete virtual machines | ✅ | ✅ | ❌ |
| Modify CPU, memory, disk | ✅ | ✅ | ❌ |
| Add or remove virtual devices | ✅ | ✅ | ❌ |
| Rename virtual machine | ✅ | ✅ | ❌ |
| Register or unregister VM | ✅ | ✅ | ❌ |

### VM power operations

| Action | Administrator | Contributor | Read-only |
|--------|---------------|-------------|-----------|
| Power on/off | ✅ | ✅ | ❌ |
| Suspend or resume | ✅ | ✅ | ❌ |
| Reset | ✅ | ✅ | ❌ |

### Snapshot management

| Action | Administrator | Contributor | Read-only |
|--------|---------------|-------------|-----------|
| Create snapshot | ✅ | ✅ | ❌ |
| Remove snapshot | ✅ | ✅ | ❌ |
| Rename snapshot | ✅ | ✅ | ❌ |
| Revert to snapshot | ✅ | ✅ | ❌ |

### Guest operations

| Action | Administrator | Contributor | Read-only |
|--------|---------------|-------------|-----------|
| Access console | ✅ | ✅ | ❌ |
| Execute guest programs | ✅ | ✅ | ❌ |
| Install VMware Tools | ✅ | ✅ | ❌ |
| Read guest info | ✅ | ✅ | ❌ |

## Networking (NSX, vSphere)

Covers all network-related permissions, including dvSwitches, logical networks, firewalls, and network assignment.

### Network configuration

| Action | Administrator | Contributor | Read-only |
|--------|---------------|-------------|-----------|
| Create or modify dvSwitch | ✅ | ❌ | ❌ |
| Create or modify port groups | ✅ | ❌ | ❌ |
| Assign VM to network | ✅ | ✅ | ❌ |
| Modify network I/O control | ✅ | ❌ | ❌ |

### NSX-T operations

| Action | Administrator | Contributor | Read-only |
|--------|---------------|-------------|-----------|
| Manage firewall rules | ✅ | ❌ | ❌ |
| Configure NAT or DHCP | ✅ | ❌ | ❌ |
| View network topology | ✅ | ✅ | ✅ |

### Miscellaneous network tasks

| Action | Administrator | Contributor | Read-only |
|--------|---------------|-------------|-----------|
| Assign IP failover | ✅ | ✅ | ❌ |
| Configure reverse DNS | ✅ | ✅ | ❌ |

## Storage & Datastores

Covers permissions related to datastore browsing, file operations, and storage policy configuration.

### Datastore access and file management

| Action | Administrator | Contributor | Read-only |
|--------|---------------|-------------|-----------|
| Browse datastore | ✅ | ✅ | ✅ |
| Allocate space | ✅ | ✅ | ❌ |
| Upload / delete files | ✅ | ✅ | ❌ |
| Move files between datastores | ✅ | ✅ | ❌ |
| Rename or update VM files | ✅ | ✅ | ❌ |

### Datastore configuration

| Action | Administrator | Contributor | Read-only |
|--------|---------------|-------------|-----------|
| Configure datastore settings | ✅ | ❌ | ❌ |
| Perform low-level file operations | ✅ | ❌ | ❌ |
| Manage datastore clusters | ✅ | ❌ | ❌ |

### Profile-driven storage

| Action | Administrator | Contributor | Read-only |
|--------|---------------|-------------|-----------|
| View storage profiles | ✅ | ✅ | ❌ |
| Update profile-driven storage | ✅ | ✅ | ❌ |

## vApp & Guest operations

This section includes actions related to vApp management, guest interaction, and deployment from OVF templates.

### vApp lifecycle

| Action | Administrator | Contributor | Read-only |
|--------|---------------|-------------|-----------|
| Create / delete vApp | ✅ | ✅ | ❌ |
| Clone vApp | ✅ | ✅ | ❌ |
| Import / export vApp | ✅ | ✅ | ❌ |
| Rename or move vApp | ✅ | ✅ | ❌ |
| Power on/off/suspend vApp | ✅ | ✅ | ❌ |

### vApp configuration

| Action | Administrator | Contributor | Read-only |
|--------|---------------|-------------|-----------|
| Modify vApp resources | ✅ | ❌ | ❌ |
| Configure application / instance settings | ✅ | ❌ | ❌ |
| Assign vApp to resource pool | ✅ | ✅ | ❌ |

### OVF & template operations

| Action | Administrator | Contributor | Read-only |
|--------|---------------|-------------|-----------|
| Deploy from OVF | ✅ | ✅ | ❌ |
| View OVF environment | ✅ | ✅ | ❌ |
| Customize guest during deployment | ✅ | ✅ | ❌ |

## Backup & Restore

Covers permissions related to enabling, disabling, and restoring backups for virtual machines.

| Action | Administrator | Contributor | Read-only |
|--------|---------------|-------------|-----------|
| Enable backup | ✅ | ❌ | ❌ |
| Disable backup | ✅ | ❌ | ❌ |
| View backup list | ✅ | ✅ | ✅ |
| Restore from backup | ✅ | ✅ | ❌ |

## Tagging

Covers permissions for managing vSphere tags and tag categories.

### Tag and category operations

| Action | Administrator | Contributor | Read-only |
|--------|---------------|-------------|-----------|
| Create vSphere tag | ✅ | ✅ | ❌ |
| Delete vSphere tag | ✅ | ✅ | ❌ |
| Edit vSphere tag | ✅ | ✅ | ❌ |
| Create tag category | ✅ | ✅ | ❌ |
| Edit tag category | ✅ | ✅ | ❌ |
| Delete tag category | ✅ | ✅ | ❌ |

### Assigning and unassigning tags

| Action | Administrator | Contributor | Read-only |
|--------|---------------|-------------|-----------|
| Assign/unassign tag to object | ✅ | ✅ | ❌ |
| Assign/unassign tag globally | ✅ | ✅ | ❌ |

## Lifecycle Management

Covers permissions for using VMware vSphere Lifecycle Manager (vLCM), including baselines, patching, and compliance scanning.

### Lifecycle Manager actions

| Action | Administrator | Contributor | Read-only |
|--------|---------------|-------------|-----------|
| Attach baseline | ✅ | ❌ | ❌ |
| Manage baseline content | ✅ | ❌ | ❌ |
| Stage patches and upgrades | ✅ | ❌ | ❌ |
| Remediate to apply patches | ✅ | ❌ | ❌ |
| Scan for applicable patches | ✅ | ❌ | ❌ |
| View compliance status | ✅ | ✅ | ❌ |
| Upload upgrade images | ✅ | ❌ | ❌ |

## Alarms

Covers actions related to alarms within the vSphere environment.

| Action | Administrator | Contributor | Read-only |
|--------|---------------|-------------|-----------|
| Acknowledge alarm | ✅ | ✅ | ✅ |
| Set alarm status | ✅ | ✅ | ❌ |
| Create new alarm | ✅ | ❌ | ❌ |
| Modify alarm configuration | ✅ | ❌ | ❌ |
| Disable alarm action | ✅ | ❌ | ❌ |
| Remove alarm | ✅ | ❌ | ❌ |

## Folders & Resources

Covers operations on folders, resource pools, and related structural elements in vSphere.

### Folder operations

| Action | Administrator | Contributor | Read-only |
|--------|---------------|-------------|-----------|
| Create folder | ✅ | ❌ | ❌ |
| Delete folder | ✅ | ❌ | ❌ |
| Move folder | ✅ | ❌ | ❌ |
| Rename folder | ✅ | ❌ | ❌ |

### Resource pool operations

| Action | Administrator | Contributor | Read-only |
|--------|---------------|-------------|-----------|
| Create resource pool | ✅ | ❌ | ❌ |
| Modify resource pool | ✅ | ❌ | ❌ |
| Move resource pool | ✅ | ❌ | ❌ |
| Assign VM to resource pool | ✅ | ✅ | ❌ |
| Assign vApp to resource pool | ✅ | ✅ | ❌ |
| Remove or rename resource pool | ✅ | ❌ | ❌ |

## Advanced & Internal Operations

### Common advanced operations

These are advanced platform operations related to security, automation, and infrastructure control.

#### Encryption and KMS management

| Action | Administrator | Contributor | Read-only |
|--------|---------------|-------------|-----------|
| Encrypt/decrypt VM | ✅ | ✅ | ❌ |
| Recrypt | ✅ | ✅ | ❌ |
| Manage keys | ✅ | ❌ | ❌ |
| Manage encryption policies | ✅ | ❌ | ❌ |
| Read KMS information | ✅ | ✅ | ❌ |
| Manage KMS servers | ✅ | ❌ | ❌ |

#### Session and task management

| Action | Administrator | Contributor | Read-only |
|--------|---------------|-------------|-----------|
| Send session messages | ✅ | ❌ | ❌ |
| Validate session | ✅ | ❌ | ❌ |
| Cancel running tasks | ✅ | ✅ | ❌ |
| Create, modify, or delete scheduled tasks | ✅ | ✅ | ❌ |

#### Host configuration

| Action | Administrator | Contributor | Read-only |
|--------|---------------|-------------|-----------|
| Enter/exit maintenance mode | ✅ | ❌ | ❌ |
| Reboot or shut down host | ✅ | ❌ | ❌ |
| Change SNMP/date/PCI settings | ✅ | ❌ | ❌ |
| Manage firmware

### Rare/internal operations 

This section includes actions that are rarely used by most users but are part of the full technical permission matrix. They are typically reserved for automation, troubleshooting, or internal OVHcloud operations.

| Action | Administrator | Contributor | Read-only |
|--------|---------------|-------------|-----------|
| Register extension | ✅ | ❌ | ❌ |
| CIM interaction (host diagnostics) | ✅ | ❌ | ❌ |
| Configure network protocol profile | ✅ | ❌ | ❌ |
| Inject USB HID scan codes | ✅ | ❌ | ❌ |
| Replay session on virtual machine | ✅ | ❌ | ❌ |
| VSPAN operation (switch traffic mirroring) | ✅ | ❌ | ❌ |

> ℹ️ These actions are generally not visible in the OVHcloud Manager or vSphere UI, and are only relevant in advanced or automated contexts.

## Go further

If you need training or technical assistance to implement our solutions, please contact your Technical Account Manager or click on [this link](/links/professional-services) to get a quote and ask our Professional Services experts for a custom analysis of your project.

Ask questions, give your feedback and interact directly with the team building our Hosted Private Cloud services on the dedicated [Discord](https://discord.gg/ovhcloud) channel.

Join our [community of users](/links/community).