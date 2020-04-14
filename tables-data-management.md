# Data Management

- [Management Header](#management-header)
    - [Column Level Grouping](#column-level-grouping)
    - [Add Row](#add-row)
    - [Export Data](#export-data)
    - [Column Chooser](#column-chooser)
    - [Search ...](#Search-...)
- [Server-Side Data Viewer](#server-side-data-viewer)
    - [Server Side Header](#server-side-header)
    - [Server Side Body](#server-side-body)
    - [Server Side Body](#server-side-body)

- [Client-Side Data Viewer](#client-side-data-viewer)

<a name="introduction"></a>

## Introduction

The **Data Management Header** provides the opportunity to customize your data display as well as table-level actions that are dependent on your security access. The table grids allow for many display customizations and row by row record modifications. These customization and record-modification options depend on the data viewer object that is displaying the table details; the **Server-Side Data Viewer** or the **Client-Side Data Viewer**.

## Data Management Header

- ### Column Level Grouping

    In the top left of the Grid Header is the following instruction **Drag a column header here to group by that column**.  The data viewer columns can be dragged.  In one use case, if you wanted to all of the customers for a given state, you would drag the **State** column onto the header and the grid would give you a list of every customer on a state by state level.

    Multiple levels of grouping are enabled by simply repeating the step above.

- ### Add Row

    An **Add a Row +** icon gives you a form for you to add a new record to the table.

- ### Export Data

    An **Export Data** icon allows you to export data in different ways depending on the type of grid selected. You may want to download data from a foreflow table to analyze it in Excel or use it in another application or system.  To do this, use the **Export Data** feature.
 
    (image here)
    
    The export process is different depending on the [Properties](tables-properties.md) setup.  If the **Use Client Side Data Viewer** setting for the table from which you are exporting data is set to **False**, you will then see a dialog box appear with **Queue Export** and **Cancel** options.  When you select **Queue Export**, foreflow schedules a **Task** that exports the data.  When foreflow completes the export, you will receive an email with a **Download File** link.  Clicking this will download your data in .xlsx format.

    If the **Use Client Side Data Viewer** setting for the table from which you are exporting data is set to **True**, the data you've selected will download immediately in .xlsx format.

- ### Column Chooser

    A **Column Chooser** icon lets you hide or show columns as you want to.

- ### Search ...

    A **Search...** option gives you a full-text search across your entire table.

## Server Side Data Viewer

The **Server-Side Data Viewer** is the default setting for viewing table details.  Because it is a server filled viewer, the data on each page of the detail is fetched each time a page is changed.  This set up provides a reliable and reasonably fast view of any size table.  

- ### Server Side Headers

    - **Column Order**: You can change your display column order by simply dragging the Column Header to the position you want to see it.

    - **Row Order**: You can order your records by clicking on a column header and changing the order-by orientation icon 

- ### Server Side Actions

    **Server-Side Actions** are permissions-based on both User Permissions level and a [Properties](tables-properties) level. For example:  If a table's _Read Only_ toggle is set to _false_ and a User's permission is set to _Update_, then the Edit icon will be visible.

    - #### Server Side Edit

        When you click on the **Edit** icon, you have the permissions-based ability to edit a record's fields in one of the following ways based on how your table administrator sets the Editing Mode on in the [Properties](tables-properties#editing-mode) page.
        - Cell
        - Row
        - In-Line Pop-up Form
        - Pop-up Form

    - #### Server Side Delete

        You also have the permissions-based capability to delete records by clicking on the **Delete** icon. If deletes have been made a **Show Deleted Records** or **Hide Deleted Records** button appears in the table header.  When deleted records are displayed, the deleted record will appear with an **Undo** icon in the record actions in case the delete was made by mistake.

    - #### Server Side Audit

        There is a robust, permissions-based auditing system that will allow you to track the changes throughout the lifecycle of an evolving record by clicking on the **Audit** icon.  If the record is replaced then the audit trail is removed.

    - #### Server Side Forms

        If forms have been created on [Properties](tables-properties#forms-section) page then a permissions-based **Forms** icon also appears according to the business logic set in the properties page.

## Client-Side Data Viewer

### Client Side Header


### Client Side Body


### Client Side Actions