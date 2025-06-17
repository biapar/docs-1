---
title: 'Full permissions matrix by role and scope for Hosted Private Cloud'
excerpt: 'Explore all available actions by role (RW, RO, Operator) across vSphere, VM Network and V(x)lans for each category of the Hosted Private Cloud platform.'
updated: 2025-06-20
---

## Objective

**This guide provides the complete technical permissions breakdown by category, scope, and user role across the OVHcloud Hosted Private Cloud platform.**

Each section lists what a user with a given role (RW, RO, Operator…) can do on components like vSphere, VM Network, and V(x)lans.

> [!primary]
> Role names may vary depending on the interface:
> - **RW / RO / Operator** (vSphere UI)
> - **NetAdmin / NetManager / Read-only** (NSX-T)
> - **vDS Administrator / NetworkAdmin** (advanced network contexts)

## Requirements

You must have access to a Hosted Private Cloud environment with role-based access control enabled.

## Instructions

Below is the complete list of permissions available for each category and role across vSphere, VM Network, and V(x)lans.

### Alarms

<table>
  <thead>
    <tr>
      <th rowspan="2">Action</th>
      <th colspan="2">vSphere</th>
      <th colspan="3">VM Network</th>
      <th colspan="3">V(x)lans</th>
    </tr>
    <tr>
      <th>RW</th><th>RO</th>
      <th>NetAdmin</th><th>RO</th><th>NetManager</th>
      <th>Administrator</th><th>Operator</th><th>Read-Only</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Acknowledge alarm</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Create alarm</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Disable alarm action</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Modify alarm</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Remove alarm</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Set alarm status</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
  </tbody>
</table>

### Cryptographic operations

<table>
  <thead>
    <tr>
      <th rowspan="2">Action</th>
      <th colspan="2">vSphere</th>
      <th colspan="3">VM Network</th>
      <th colspan="3">V(x)lans</th>
    </tr>
    <tr>
      <th>RW</th><th>RO</th>
      <th>NetAdmin</th><th>RO</th><th>NetManager</th>
      <th>Administrator</th><th>Operator</th><th>Read-Only</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Add disk</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Clone</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Decrypt</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Direct Access</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Encrypt</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Encrypt new</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Manage KMS</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Manage encryption policies</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Manage keys</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Migrate</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Read KMS information</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Recrypt</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Register VM</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Register host</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
  </tbody>
</table>

### dvPort group

<table>
  <thead>
    <tr>
      <th rowspan="2">Action</th>
      <th colspan="2">vSphere</th>
      <th colspan="3">VM Network</th>
      <th colspan="3">V(x)lans</th>
    </tr>
    <tr>
      <th>RW</th><th>RO</th>
      <th>NetAdmin</th><th>RO</th><th>NetManager</th>
      <th>Administrator</th><th>Operator</th><th>Read-Only</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Create</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Delete</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Modify</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Policy operation</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Scope operation</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
  </tbody>
</table>

### Distributed switch

<table>
  <thead>
    <tr>
      <th rowspan="2">Action</th>
      <th colspan="2">vSphere</th>
      <th colspan="3">VM Network</th>
      <th colspan="3">V(x)lans</th>
    </tr>
    <tr>
      <th>RW</th><th>RO</th>
      <th>NetAdmin</th><th>RO</th><th>NetManager</th>
      <th>Administrator</th><th>Operator</th><th>Read-Only</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Modify</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Network I/O control operation</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Policy operation</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Port configuration operation</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Port setting operation</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>VSPAN operation</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
  </tbody>
</table>

### Datacenter

<table>
  <thead>
    <tr>
      <th rowspan="2">Action</th>
      <th colspan="2">vSphere</th>
      <th colspan="3">VM Network</th>
      <th colspan="3">V(x)lans</th>
    </tr>
    <tr>
      <th>RW</th><th>RO</th>
      <th>NetAdmin</th><th>RO</th><th>NetManager</th>
      <th>Administrator</th><th>Operator</th><th>Read-Only</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Network protocol profile configuration</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
  </tbody>
</table>

### Datastore

<table>
  <thead>
    <tr>
      <th rowspan="2">Action</th>
      <th colspan="2">vSphere</th>
      <th colspan="3">VM Network</th>
      <th colspan="3">V(x)lans</th>
    </tr>
    <tr>
      <th>RW</th><th>RO</th>
      <th>NetAdmin</th><th>RO</th><th>NetManager</th>
      <th>Administrator</th><th>Operator</th><th>Read-Only</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Allocate space</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Browse datastore</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Configure datastore</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Low level file operations</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Move datastore</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Remove file</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Update virtual machine files</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Update virtual machine metadata</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
  </tbody>
</table>

### Extension

<table>
  <thead>
    <tr>
      <th rowspan="2">Action</th>
      <th colspan="2">vSphere</th>
      <th colspan="3">VM Network</th>
      <th colspan="3">V(x)lans</th>
    </tr>
    <tr>
      <th>RW</th><th>RO</th>
      <th>NetAdmin</th><th>RO</th><th>NetManager</th>
      <th>Administrator</th><th>Operator</th><th>Read-Only</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Register extension</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
  </tbody>
</table>

### Folder

<table>
  <thead>
    <tr>
      <th rowspan="2">Action</th>
      <th colspan="2">vSphere</th>
      <th colspan="3">VM Network</th>
      <th colspan="3">V(x)lans</th>
    </tr>
    <tr>
      <th>RW</th><th>RO</th>
      <th>NetAdmin</th><th>RO</th><th>NetManager</th>
      <th>Administrator</th><th>Operator</th><th>Read-Only</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Create folder</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Delete folder</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Move folder</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Rename folder</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
  </tbody>
</table>

### Global

<table>
  <thead>
    <tr>
      <th rowspan="2">Action</th>
      <th colspan="2">vSphere</th>
      <th colspan="3">VM Network</th>
      <th colspan="3">V(x)lans</th>
    </tr>
    <tr>
      <th>RW</th><th>RO</th>
      <th>NetAdmin</th><th>RO</th><th>NetManager</th>
      <th>Administrator</th><th>Operator</th><th>Read-Only</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Act as vCenter Server</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Cancel task</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Capacity planning</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Diagnostics</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Disable methods</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Enable methods</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Global tag</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Health</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Licenses</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Log event</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Manage custom attribute</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Proxy</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Set custom attribute</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>System tag</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
  </tbody>
</table>

### Host

<table>
  <thead>
    <tr>
      <th rowspan="2">Action</th>
      <th colspan="2">vSphere</th>
      <th colspan="3">VM Network</th>
      <th colspan="3">V(x)lans</th>
    </tr>
    <tr>
      <th>RW</th><th>RO</th>
      <th>NetAdmin</th><th>RO</th><th>NetManager</th>
      <th>Administrator</th><th>Operator</th><th>Read-Only</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>CIM</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>CIM interaction</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Configuration</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Advanced settings</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Change PciPassthru settings</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Change SNMP settings</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Change date and time settings</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Firmware</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Maintenance</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Memory configuration</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Power</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Query patch</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Storage partition configuration</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>System Management</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>System resources</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Virtual machine autostart configuration</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Inventory</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Create cluster</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Modify cluster</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Move cluster or standalone host</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Move host</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Remove cluster</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Remove host</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Rename cluster</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Local operations</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Create virtual machine</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Delete virtual machine</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Manage user groups</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Reconfigure virtual machine</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
  </tbody>
</table>

### vSphere Tagging

<table>
  <thead>
    <tr>
      <th rowspan="2">Action</th>
      <th colspan="2">vSphere</th>
      <th colspan="3">VM Network</th>
      <th colspan="3">V(x)lans</th>
    </tr>
    <tr>
      <th>RW</th><th>RO</th>
      <th>NetAdmin</th><th>RO</th><th>NetManager</th>
      <th>Administrator</th><th>Operator</th><th>Read-Only</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Assign or Unassign vSphere Tag</td>
      <td>✅</td>
      <td>❌</td>
      <td>✅</td>
      <td>❌</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Assign or Unassign vSphere Tag on Object</td>
      <td>✅</td>
      <td>❌</td>
      <td>✅</td>
      <td>❌</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Create vSphere Tag</td>
      <td>✅</td>
      <td>❌</td>
      <td>✅</td>
      <td>❌</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Create vSphere Tag Category</td>
      <td>✅</td>
      <td>❌</td>
      <td>✅</td>
      <td>❌</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Delete vSphere Tag</td>
      <td>✅</td>
      <td>❌</td>
      <td>✅</td>
      <td>❌</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Delete vSphere Tag Category</td>
      <td>✅</td>
      <td>❌</td>
      <td>✅</td>
      <td>❌</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Edit vSphere Tag</td>
      <td>✅</td>
      <td>❌</td>
      <td>✅</td>
      <td>❌</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Edit vSphere Tag Category</td>
      <td>✅</td>
      <td>❌</td>
      <td>✅</td>
      <td>❌</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
  </tbody>
</table>

### Network

<table>
  <thead>
    <tr>
      <th rowspan="2">Action</th>
      <th colspan="2">vSphere</th>
      <th colspan="3">VM Network</th>
      <th colspan="3">V(x)lans</th>
    </tr>
    <tr>
      <th>RW</th><th>RO</th>
      <th>NetAdmin</th><th>RO</th><th>NetManager</th>
      <th>Administrator</th><th>Operator</th><th>Read-Only</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Assign network</td>
      <td>❌</td>
      <td>❌</td>
      <td>✅</td>
      <td>❌</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
  </tbody>
</table>

### Performance

<table>
  <thead>
    <tr>
      <th rowspan="2">Action</th>
      <th colspan="2">vSphere</th>
      <th colspan="3">VM Network</th>
      <th colspan="3">V(x)lans</th>
    </tr>
    <tr>
      <th>RW</th><th>RO</th>
      <th>NetAdmin</th><th>RO</th><th>NetManager</th>
      <th>Administrator</th><th>Operator</th><th>Read-Only</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Modify intervals</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
  </tbody>
</table>

### Resource

<table>
  <thead>
    <tr>
      <th rowspan="2">Action</th>
      <th colspan="2">vSphere</th>
      <th colspan="3">VM Network</th>
      <th colspan="3">V(x)lans</th>
    </tr>
    <tr>
      <th>RW</th><th>RO</th>
      <th>NetAdmin</th><th>RO</th><th>NetManager</th>
      <th>Administrator</th><th>Operator</th><th>Read-Only</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Apply recommendation</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Assign vApp to resource pool</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Assign virtual machine to resource pool</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Create resource pool</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Migrate powered off virtual machine</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Migrate powered on virtual machine</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Modify resource pool</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Move resource pool</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Query vMotion</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Remove resource pool</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Rename resource pool</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
  </tbody>
</table>

### Scheduled task

<table>
  <thead>
    <tr>
      <th rowspan="2">Action</th>
      <th colspan="2">vSphere</th>
      <th colspan="3">VM Network</th>
      <th colspan="3">V(x)lans</th>
    </tr>
    <tr>
      <th>RW</th><th>RO</th>
      <th>NetAdmin</th><th>RO</th><th>NetManager</th>
      <th>Administrator</th><th>Operator</th><th>Read-Only</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Create tasks</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Modify task</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Remove task</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Run task</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
  </tbody>
</table>

### Datastore cluster

<table>
  <thead>
    <tr>
      <th rowspan="2">Action</th>
      <th colspan="2">vSphere</th>
      <th colspan="3">VM Network</th>
      <th colspan="3">V(x)lans</th>
    </tr>
    <tr>
      <th>RW</th><th>RO</th>
      <th>NetAdmin</th><th>RO</th><th>NetManager</th>
      <th>Administrator</th><th>Operator</th><th>Read-Only</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Configure a datastore cluster</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
  </tbody>
</table>

### Sessions

<table>
  <thead>
    <tr>
      <th rowspan="2">Action</th>
      <th colspan="2">vSphere</th>
      <th colspan="3">VM Network</th>
      <th colspan="3">V(x)lans</th>
    </tr>
    <tr>
      <th>RW</th><th>RO</th>
      <th>NetAdmin</th><th>RO</th><th>NetManager</th>
      <th>Administrator</th><th>Operator</th><th>Read-Only</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Message</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Validate session</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
  </tbody>
</table>

### Profile-driven storage

<table>
  <thead>
    <tr>
      <th rowspan="2">Action</th>
      <th colspan="2">vSphere</th>
      <th colspan="3">VM Network</th>
      <th colspan="3">V(x)lans</th>
    </tr>
    <tr>
      <th>RW</th><th>RO</th>
      <th>NetAdmin</th><th>RO</th><th>NetManager</th>
      <th>Administrator</th><th>Operator</th><th>Read-Only</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Profile-driven storage update</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Profile-driven storage view</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
  </tbody>
</table>

### Storage views

<table>
  <thead>
    <tr>
      <th rowspan="2">Action</th>
      <th colspan="2">vSphere</th>
      <th colspan="3">VM Network</th>
      <th colspan="3">V(x)lans</th>
    </tr>
    <tr>
      <th>RW</th><th>RO</th>
      <th>NetAdmin</th><th>RO</th><th>NetManager</th>
      <th>Administrator</th><th>Operator</th><th>Read-Only</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Configure service</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>View</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
  </tbody>
</table>

### Tasks

<table>
  <thead>
    <tr>
      <th rowspan="2">Action</th>
      <th colspan="2">vSphere</th>
      <th colspan="3">VM Network</th>
      <th colspan="3">V(x)lans</th>
    </tr>
    <tr>
      <th>RW</th><th>RO</th>
      <th>NetAdmin</th><th>RO</th><th>NetManager</th>
      <th>Administrator</th><th>Operator</th><th>Read-Only</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Create task</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Update task</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
  </tbody>
</table>

### vApp

<table>
  <thead>
    <tr>
      <th rowspan="2">Action</th>
      <th colspan="2">vSphere</th>
      <th colspan="3">VM Network</th>
      <th colspan="3">V(x)lans</th>
    </tr>
    <tr>
      <th>RW</th><th>RO</th>
      <th>NetAdmin</th><th>RO</th><th>NetManager</th>
      <th>Administrator</th><th>Operator</th><th>Read-Only</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Add virtual machine</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Assign resource pool</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Assign vApp</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Clone</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Create</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Delete</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Export</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Import</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Move</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Power off</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Power on</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Rename</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Suspend</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Unregister</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>View OVF environment</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>vApp application configuration</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>vApp instance configuration</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>vApp resource configuration</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
  </tbody>
</table>

### VMware vSphere Lifecycle Manager

<table>
  <thead>
    <tr>
      <th rowspan="2">Action</th>
      <th colspan="2">vSphere</th>
      <th colspan="3">VM Network</th>
      <th colspan="3">V(x)lans</th>
    </tr>
    <tr>
      <th>RW</th><th>RO</th>
      <th>NetAdmin</th><th>RO</th><th>NetManager</th>
      <th>Administrator</th><th>Operator</th><th>Read-Only</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Configure</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Configure Service</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Manage Baseline</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Attach Baseline</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Manage Baseline</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Manage Patches and Upgrades</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Remediate to Apply Patches, Extensions, and Upgrades</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Scan for Applicable Patches, Extensions, and Upgrades</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Stage Patches and Extensions</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>View Compliance Status</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Upload file</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Upload upgrade images and offline bundles</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
  </tbody>
</table>

### Virtual machine

<table>
  <thead>
    <tr>
      <th rowspan="2">Action</th>
      <th colspan="2">vSphere</th>
      <th colspan="3">VM Network</th>
      <th colspan="3">V(x)lans</th>
    </tr>
    <tr>
      <th>RW</th><th>RO</th>
      <th>NetAdmin</th><th>RO</th><th>NetManager</th>
      <th>Administrator</th><th>Operator</th><th>Read-Only</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Change Configuration</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Acquire disk lease</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Add existing disk</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Add new disk</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Add or remove device</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Advanced configuration</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Change CPU count</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Change Memory</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Change Settings</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Change Swapfile placement</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Change resource</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Configure Raw device</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Configure managedBy</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Display connection settings</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Extend virtual disk</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Modify device settings</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Query Fault Tolerance compatibility</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Query unowned files</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Reload from path</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Remove disk</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Rename</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Reset guest information</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Set annotation</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Toggle disk change tracking</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Toggle fork parent</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Upgrade virtual machine compatibility</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Edit Inventory</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Create from existing</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Create new</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Move</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Register</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Remove</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Unregister</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
  </tbody>
</table>

### Guest operations

<table>
  <thead>
    <tr>
      <th rowspan="2">Action</th>
      <th colspan="2">vSphere</th>
      <th colspan="3">VM Network</th>
      <th colspan="3">V(x)lans</th>
    </tr>
    <tr>
      <th>RW</th><th>RO</th>
      <th>NetAdmin</th><th>RO</th><th>NetManager</th>
      <th>Administrator</th><th>Operator</th><th>Read-Only</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Guest operation modifications</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Guest operation program execution</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Guest operation queries</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Interaction</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Answer question</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Backup operation on virtual machine</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Configure CD media</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Configure floppy media</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Connect devices</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Console interaction</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Create screenshot</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Defragment all disks</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Guest operating system management by VIX API</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Inject USB HID scan codes</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Install VMware Tools</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Perform wipe or shrink operations</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Power off</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Power on</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Record session on virtual machine</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Replay session on virtual machine</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Reset</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Resume Fault Tolerance</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Suspend</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Suspend Fault Tolerance</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Test failover</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Test restart Secondary VM</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Turn off Fault Tolerance</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Turn on Fault Tolerance</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
  </tbody>
</table>

### Provisioning

<table>
  <thead>
    <tr>
      <th rowspan="2">Action</th>
      <th colspan="2">vSphere</th>
      <th colspan="3">VM Network</th>
      <th colspan="3">V(x)lans</th>
    </tr>
    <tr>
      <th>RW</th><th>RO</th>
      <th>NetAdmin</th><th>RO</th><th>NetManager</th>
      <th>Administrator</th><th>Operator</th><th>Read-Only</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Allow disk access</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Allow read-only disk access</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Allow virtual machine download</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Allow virtual machine files upload</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Clone template</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Clone virtual machine</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Create template from virtual machine</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Customize guest</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Deploy template</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Mark as template</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Mark as virtual machine</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Modify customization specification</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Promote disks</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Read customization specifications</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
  </tbody>
</table>

### Infrastructure and Backup Operations

<table>
  <thead>
    <tr>
      <th rowspan="2">Action</th>
      <th colspan="2">vSphere</th>
      <th colspan="3">VM Network</th>
      <th colspan="3">V(x)lans</th>
    </tr>
    <tr>
      <th>RW</th><th>RO</th>
      <th>NetAdmin</th><th>RO</th><th>NetManager</th>
      <th>Administrator</th><th>Operator</th><th>Read-Only</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Create snapshot</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Remove snapshot</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Rename snapshot</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Revert to snapshot</td>
      <td>✅</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Add Host</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Add Storage</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>View Backups</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Enable Backup</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Disable Backup</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Restore Backup</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>View Public IP Blocks</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td>Configure IP Reverse DNS</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
  </tbody>
</table>

## Go further

If you need training or technical assistance to implement our solutions, please contact your Technical Account Manager or click on [this link](/links/professional-services) to get a quote and ask our Professional Services experts for a custom analysis of your project.

Ask questions, give your feedback and interact directly with the team building our Hosted Private Cloud services on the dedicated [Discord](https://discord.gg/ovhcloud) channel.

Join our [community of users](/links/community).