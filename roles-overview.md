# Roles Overview

-   [Introduction](#introduction)
    -   [Roles](#roles)
    -   [Permissions](#permissions)
-   [Creating Roles](#creating-roles)
-   [Editing Roles](#editing-roles)
    -   [Changing Role Properties](#changing-role-properties)
    -   [Adding Users](#adding-users)
-   [Updating Permissions](#updating-permissions)
    -   [Existing Permissions](#existing-permissions)
    -   [Category Permissions](#category-permissions)
    -   [Specific Permissions](#specific-permissions)

<a name="introduction"></a>

## Introduction

One of the features of foreflow is the ability to create robust Role-based permissions. The ability to create roles is a permissions-based option in the main foreflow menu reserved for administrators. 

<a name="roles"></a>

- **Roles** &mdash; What are Roles?  Roles are structures that allow a pre-determined set of permissions to be applied to multiple users without having to recreate that set for each user.

<a name="Permissions"></a>

- **Permissions** &mdash; What are Permissions? Permissions are a set of actions, _CREATE, READ, UPDATE and DELETE_ that are selectively permitted for individual _Users_ or _Roles_.


This Role-based permissions framework can be applied to both categories and objects. The category-based permissions cover _all_ created objects within a given category. The object-based permissions apply to _specific_ created category objects. 

<a name="creating-roles"></a>

## Creating Roles

To create a role, go to the Roles page from the main menu and click the Add Role button.  This opens an _Add Role_ dialog box where you can provide a _Title_ for your role.  When you click the _Save_ button your role will appear in the _Title_ list with the ability to _Edit_ or _Delete_ the _Roles_ you have created.

<a name="editing-roles"></a>

## Editing Roles

Clicking the _Edit Details_ icon, represented by a pencil, will take you to a page with 2 panes giving you the capability to change _Role Properties_, and add specific _Users_.  After altering any values or adding users to the role, click the _Update Role_ button to accept the updates to the _Role_.  An alert will appear confirming that your _Role_ has been updated.

<a name="changing-role-properties"></a>

### Changing Role Properties

To change the _Role Properties_, a list of properties to be set is displayed in the first _Role Properties_ pane.  Change the _Value_ of that property and Update the Role.

<a name="adding-users"></a>

### Adding Users

You can add users to your role by simply typing the name in the search box.  As you begin to type _Users_ that correspond to your text pattern, matched _Users_ appear from which you can select using your arrows and hitting enter.  Once a user is selected they appear in a list of associated users beneath the search box.  Clicking the _X_ beside the associated _User_ will remove that user from the _Role-associated Users_ list.

Once the _Users_ list has been finalized, click the Update Role button to accept the updates to the Role. An alert will appear confirming that your Role has been updated.

<a name="updating-permissions"></a>

## Updating Permissions

Clicking the _Edit Permissions_ icon, represented by a lock, will take you to the Update Permissions page. This page allows you to update the permissions for the selected role.

Once you've selected the permissions for the role click the "Save" button to persist updates.

<a name="existing-permissions"></a>

### Existing Permissions

The first panel shows the list of available entities and icons to represent the current permissions for each entity. Clicking on an entity will display one or two additional panels depending on the available permissions for that entity.

<a name="category-permissions"></a>

### Category Permissions

The second panel displays the available permissions for the selected entity.

> **Example**: If you selected (clicked) the _Tables_ entity on the first panel, you would then see four permissions listed in the second panel; Create, See, Edit, and Remove.

Clicking on any of the available permissions toggles that permission for the current role.

<a name="specific-permissions"></a>

### Entity Specific Permissions

The thrid panel displays the available specific permissions for the selected entity. An _Add_ button displays a pop-up to select a specific entity to modify permissions. Once you've choosen a spcecific entity and added it to the _Specific Permissions_ panel you can select (click) on that entity to modify permissions for that specific entity.

> **Example**: If you had a _Table_ named 'customers' and selected it you would see six permissions: See, Edit, Remove, Add Records, Update Records, and Remove Records.