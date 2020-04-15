# Data Management

-   [Introduction](#introduction)
-   [Management Header](#management-header)
    -   [Column Level Grouping](#column-level-grouping)
    -   [Add Row](#add-row)
    -   [Export Data](#export-data)
    -   [Column Chooser](#column-chooser)
    -   [Search](#Search)
-   [Server-Side Data Viewer](#server-side-data-viewer)

    -   [Server-Side Header](#server-side-header)
    -   [Server-Side Body](#server-side-body)
    -   [Server-Side Actions](#server-side-actions)

-   [Client-Side Data Viewer](#client-side-data-viewer)

<a name="introduction"></a>

## Introduction

The _Data Management Header_ provides the opportunity to customize your data display as well as table-level actions that are dependent on your security access. The table grids allow for many display customizations and row by row record modifications. These customization and record-modification options depend on the data viewer object that is displaying the table details; the _Server-Side Data Viewer_ or the _Client-Side Data Viewer_.

## Data Management Header

<a name="column-level-grouping"></a>

### Column Level Grouping

In the top left of the Grid Header is the following instruction _Drag a column header here to group by that column_. The data viewer columns can be dragged. In one use case, if you wanted to all of the customers for a given state, you would drag the _State_ column onto the header and the grid would give you a list of every customer on a state by state level.

Multiple levels of grouping are enabled by simply repeating the step above.

<a name="add-row"></a>

### Add Row

An _Add a Row_ **+** icon gives you a form for you to add a new record to the table.

<a name="export-data"></a>

### Export Data

-   An _Export Data_ icon allows you to export data in different ways depending on the type of grid selected. You may want to download data from a foreflow table to analyze it in Excel or use it in another application or system. To do this, use the _Export Data_ feature.

(image coming soon)

-   The export process is different depending on the [Properties](tables-properties.md) setup. If the _Use Client Side Data Viewer_ setting for the table from which you are exporting data is set to _False_, you will then see a dialog box appear with _Queue Export_ and _Cancel_ options. When you select _Queue Export_, foreflow schedules a _Task_ that exports the data. When foreflow completes the export, you will receive an email with a _Download File_ link. Clicking this will download your data in .xlsx format.

-   If the _Use Client Side Data Viewer_ setting for the table from which you are exporting data is set to _True_, the data you've selected will download immediately in .xlsx format.

<a name="column-chooser"></a>

### Column Chooser

-   A _Column Chooser_ icon opens an interface that lets you hide or show columns.

<a name="search"></a>

### Search

-   A _Search_ option gives you a full-text search across your entire table.

<a name="server-side-data-viewer"></a>

## Server-Side Data Viewer

The _Server-Side Data Viewer_ is the default setting for viewing table details. Because it is a server filled viewer, the data on each page of the detail is fetched each time an option is changed or a new page is selected. This set up provides a reliable and reasonably fast view of any size table.

<a name="server-side-column-headers"></a>

### Server-Side Column Headers

-   **Column Order** &mdash; You can change your display column order by simply dragging the Column Header to the position you want to see it.

-   **Row Order** &mdash; You can order your records by clicking on a column header and changing the order-by orientation icon

<a name="server-side-actions"></a>

### Server-Side Actions

_Server-Side Actions_ are permissions-based on both User Permissions level and a [Properties](tables-properties) level.

> **Example:** If a table's _Read Only_ toggle is set to _false_ and a User's permission is set to _Update_, then the Edit icon will be visible.

-   **Edit** &mdash; When you click on the _Edit_ icon, you have the permissions-based ability to edit a record's fields in one of the following ways based on how your table administrator sets the Editing Mode on in the [Properties](tables-properties#editing-mode) page.

    -   Cell
    -   Row
    -   In-Line Pop-up Form
    -   Pop-up Form

-   **Delete** &mdash; You also have the permissions-based capability to delete records by clicking on the _Delete_ icon. If deletes have been made a _Show Deleted Records_ or _Hide Deleted Records_ button appears in the table header. When deleted records are displayed, the deleted record will appear with an _Undo_ icon in the record actions in case the delete was made by mistake.

-   **Audit** &mdash; There is a robust, permissions-based auditing system that will allow you to track the changes throughout the lifecycle of an evolving record by clicking on the _Audit_ icon. If the record is replaced then the audit trail is removed.

-   **Forms** &mdash; If forms have been created on [Properties](tables-properties#forms-section) page then a permissions-based _Forms_ icon also appears according to the business logic set in the properties page.

<a name="client-side-data-viewer"></a>

## Client-Side Data Viewer

<a name="client-side-column-grouping"></a>

### Client-Side Column Grouping

In addition to the Column Level Grouping provided by default in the header, the Client-Side Column Grouping also adds multi-level column group ordering and the ability to do value look-ups from within the first group.

-   **Column Group Ordering** &mdash;

-   **Column Group Value Look-up** &mdash;

<a name="client-side-column-headers"></a>

### Client-Side Column Headers

-   **Column Order** &mdash; You can change your display column order by simply dragging the Column Header to the position you want to see it.

-   **Row Order** &mdash; You can order your records by clicking on a column header and changing the order-by orientation icon

-   **Values Look-up** &mdash;

-   **Logic Look-up** &mdash;

<a name="client-side-actions"></a>

### Client Side Actions

_Client-Side Actions_ are permissions-based on both User Permissions level and a [Properties](tables-properties) level. For example: If a table's _Read Only_ toggle is set to _false_ and a User's permission is set to _Update_, then the Edit icon will be visible.

-   **Edit** &mdash; When you click on the _Edit_ icon, you have the permissions-based ability to edit a record's fields in one of the following ways based on how your table administrator sets the Editing Mode on in the [Properties](tables-properties#editing-mode) page.

    -   Cell
    -   Row
    -   In-Line Pop-up Form
    -   Pop-up Form

-   **Delete** &mdash; You also have the permissions-based capability to delete records by clicking on the _Delete_ icon. If deletes have been made a _Show Deleted Records_ or _Hide Deleted Records_ button appears in the table header. When deleted records are displayed, the deleted record will appear with an _Undo_ icon in the record actions in case the delete was made by mistake.

-   **Audit** &mdash; There is a robust, permissions-based auditing system that will allow you to track the changes throughout the lifecycle of an evolving record by clicking on the _Audit_ icon. If the record is replaced then the audit trail is removed.

-   **Forms** &mdash; If forms have been created on [Properties](tables-properties#forms-section) page then a permissions-based _Forms_ icon also appears according to the business logic set in the properties page.
