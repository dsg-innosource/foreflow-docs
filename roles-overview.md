# Roles Overview

-   [Introduction](#introduction)
    -   [Roles](#roles)
    -   [Permissions](#permissions)
-   [Creating Roles](#creating-roles)
-   [Editing Roles](#editing-roles)
    -   [Changing Role Properties](#changing-role-properties)
    -   [Configuring Permissions](#configuring-permissions)
    -   [Adding Users](#adding-users)

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

Clicking the _Edit_ icon will take you to a page with 3 panes giving you the capability to change _Role Properties_, Configure _Permissions_, and add specific _Users_.  After altering, configuring or adding anything to the role, click the _Update Role_ button to accept the updates to the _Role_.  An alert will appear confirming that your _Role_ has been updated.

<a name="changing-role-properties"></a>

### Changing Role Properties

To change the _Role Properties_, a list of properties to be set is displayed in the first _Role Properties_ pane.  Change the _Value_ of that property and Update the Role.

<a name="configuring-permissions"></a>

### Configuring Permissions

-   **Add**  &mdash; Clicking the _Add_ button in the _Permissions_ panel will open an _Add Permission_ dialog box allowing you to select a _Category_ to which you want to add a permission.  Once selected, you can choose between a _Category Level_ or _Specific [Category Object]_ level permission 
    
    -   **Category Level**  &mdash; If you select the _Category Level_ you can _Choose Permissions_ by simply clicking the CheckBoxes under the CREATE, READ, UPDATE and DELETE options.  These permissions will then appear

    > For Example: If you selected the _Category Level_, you could choose the _Tables_ Category and check the _READ_ permission to allow everyone in this role to see the _Tables_.
    
    -   **Specific [Category Object]**  &mdash; If you select the _Specific [Category Object]_, a list of all those category objects will appear for you to choose from.  After choosing the specific category object, you can _Choose Permissions_ by simply clicking the CheckBoxes under the CREATE, READ, UPDATE and DELETE options.  These permissions will then appear for that category object.

    > For example: If the Category you chose was _Tables_, you could choose the _Specific [Category Object]_ of the _Employees_ table from the list of all the _Tables_, _[Category Objects]_, that are available to you.  Checking the _READ_ and _UPDATE_ _Permissions_ will allow this role to change the _Employees Table_ Definition.
    > </br></br>If you were also to choose the Category of _Table Data_, and Choose the _Specific [Category Object]_ of the _Employees_ table again, Checking the CREATE, UPDATE and DELETE options would allow your role to Create, Update and Delete records in the _Employees_ table as well.

    Once the permissions have been added, click the Update Role button to accept the updates to the Role. An alert will appear confirming that your Role has been updated.

-   **Edit**  &mdash; Once _Permissions_ have been added for either the _Category Level_ or the _Specific [Category Object]_ level, you can alter or delete the _Permissions_ by simply clicking the CheckBoxes under the CREATE, READ, UPDATE and DELETE columns or clicking the _Trash Can_ icon to entirely delete the permission record.

    Once the permissions have been edited, click the Update Role button to accept the updates to the Role. An alert will appear confirming that your Role has been updated.

<a name="adding-users"></a>

### Adding Users

You can add users to your role by simply typing the name in the search box.  As you begin to type _Users_ that correspond to your text pattern, matched _Users_ appear from which you can select using your arrows and hitting enter.  Once a user is selected they appear in a list of associated users beneath the search box.  Clicking the _X_ beside the associated _User_ will remove that user from the _Role-associated Users_ list.

Once the _Users_ list has been finalized, click the Update Role button to accept the updates to the Role. An alert will appear confirming that your Role has been updated.

