# Table Properties

-   [Introduction](#introduction)
-   [Edit Table Properties Header](#edit-table-properties-header)
    -   [Edit _Table Friendly Name_ Table Properties Navigation](#edit-_table-friendly-name_-table-properties-navigation)
    -   [Truncate Table](#truncate-table)
    -   [Table Actions](#table-actions)
-   [Table Properties Section](#table-properties-section)
    -   [Table Friendly Name](#table-friendly-name)
    -   [Table Description](#table-description)
    -   [Database Table Name](#database-table-name)
    -   [Default Number of Rows to Display](#default-number-of-rows-to-display)
    -   [Editing Mode](#editing-mode)
    -   [Default Sort](#default-sort)
    -   [Email Import](#email-import)
    -   [Use Client-Side Data Viewer](#use-client-side-data-viewer)
    -   [Display Column Chooser](#display-column-chooser)
    -   [Allow Data Export](#allow-data-export)
    -   [Enable Word Wrap](#enable-word-wrap)
    -   [Read Only](#read-only)
-   [Relationships Section](#relationships-section)
-   [Forms Section](#forms-section)
    -   [Create Form](#create-form)
-   [Column Properties Section](#column-properties-section)
    -   [Add Column](#add-column)
    -   [Default Column Definition and Display Options](#default-column-definition-and-display-options)
    -   [Type-Based Column Definitions](#type-based-column-definitions)
    -   [Standard-Type Definition Options](#standard-type-definition-options)
    -   [Reference-Type Definition Options](#reference-type-definition-options)
    -   [Calculated-Type Definition Options](#calculated-type-definition-options)
-   [Tags Section](#tags-section)

<a name="introduction"></a>

## Introduction

After selecting a particular table, you can access its properties by clicking the _Properties_ button. The properties page is divided into several sections due to the many options available. After you set all the properties that you want to be in effect for this table, be sure to click the _Update Table Properties_.

<a name="edit-table-properties-header"></a>

## Edit Table Properties Header

<a name="edit-_table-friendly-name_-table-properties-navigation"></a>

### Edit _Table Friendly Name_ Table Properties Navigation

In the Edit _Table Friendly Name_ Table Properties Header the _Table Friendly Name_ appears as a link that will take you back to the display page

<a name="truncate-table"></a>

### Truncate Table

The _Truncate Table_ button gives you the option to remove all of the data contained in your table. Clicking on that button will open a confirmation dialog box explaining that removing all the data from the table cannot be undone. Clicking _Yes_ will truncate the table.

<a name="table-actions"></a>

### Table Actions

Details on _Table Actions_ can be found on the dedicated [Table Actions](tables-actions) page.

<a name="table-properties-section"></a>

## Table Properties Section

Here you will find the general table properties:

<a name="table-friendly-name"></a>

### Table Friendly Name

This is a user-friendly or business-friendly display name for the table. This name can be edited by a user with appropriate rights.

<a name="table-description"></a>

### Table Description

This is the explanation of the contents and purpose of this data set. This description can be edited by a user with appropriate rights.

<a name="database-table-name"></a>

### Database Table Name

This is the system name of the table. It cannot be edited.

<a name="default-number-of-rows-to-display"></a>

### Default Number of Rows to Display

This sets the number of rows that will display on each page of the table grid.

<a name="editing-mode"></a>

### Editing Mode

Here you will find editing options for users with sufficient rights.

<a name="cell"></a>

-   **Cell** &mdash; When you select the _Cell_ option, the user can click on a cell to update it. The active cell is underlined.

    -   To _Accept_ the change, click the _check mark_.
    -   To _Cancel_ the edit, click the _X_.

<a name="row"></a>

-   **Row** &mdash; When you select the _Row_ option, the user must select the edit icon before clicking on a cell to update it. The active cell is underlined.

    -   To _Accept_ the change, click the _check mark_.
    -   To _Cancel_ the edit, click the _X_.

<a name="inline-form"></a>

-   **Inline Form** &mdash; When you select the _Inline Form_ option, clicking the edit icon will replace the line with a form for the user to edit. The active cell is underlined.

    -   To _Accept_ the change, click the _check mark_.
    -   To _Cancel_ the edit, click the _X_.

<a name="pop-up-form"></a>

-   **Pop-up Form** &mdash; When you select the _Pop-up Form_ option, clicking the edit icon will open a pop-up window form for the user to edit.

    -   To _Accept_ the change, click the _Save_ button.
    -   To _Cancel_ the edit, click the _Cancel_ button.

<a name="default-sort"></a>

### Default Sort

This is where you can select one of the columns on the table as your default sorting column.

<a name="sort-direction"></a>

-   **Sort Direction** &mdash; When you select either _Ascending_ or _Descending_ this direction is applied to the _Default Sort_ column that you have selected.

<a name="email-import"></a>

### Email Import

Here you will be configuring a way to either append or replace data in your table by utilizing an email attachment. When you click on the _Configure Email Import_ button a pop up will appear which contains an interactive file upload box. When you either drop or select a data file with headers, the following things occur.

-   The system generates a _table-specific_ email address of this pattern _[Universally\_Unique\_ID]@[your\_foreflow\_domain].com_. You will need to use this address to append or replace formatted data in your table

-   The system attempts to match the headers on that formatted data file to the columns in your table. After this, the system makes an interface available which allows you to adjust those matches that id cannot match on its own.

-   You are then asked to choose whether you want this formatted file to _Append To_ or _Replace_ the data in your table.

When you attach a formatted data file to an email to the generated address, the system will either append or replace the data in your table with the data in your file, depending on the action you configured.

<a name="use-client-side-data-viewer"></a>

### Use Client-Side Data Viewer

This is where you can choose to display your table in either a server-paged data grid or the Client-Side Data Viewer. While the Client-Side Data Viewer has greater functionality associated with it, the quantity of the data is significantly limited (10,000 rows) due to the memory constraints of your Client-Side computer and the web browser you are using. This value defaults to _False_.

<a name="display-column-chooser"></a>

### Display Column Chooser

Here you can choose whether or not the users of this grid will have the ability to see and choose columns to display for this data table. If the _Display Column Chooser_ is set to _False_ then the _Column Chooser_ icon will be _unavailable_ to the user. The only columns that are displayed will be those whose property _IS SHOWN BY DEFAULT_ is checked in the _Column Properties_ setup below.

<a name="allow-data-export"></a>

### Allow Data Export

Here you can choose whether or not the users of this grid will have the ability to export the data in this table. If the _Allow Data Export_ is set to _False_ then the _Export Data_ icon will be _unavailable_ to the user.

<a name="enable-word-wrap"></a>

### Enable Word Wrap

This is where you can choose to allow the height of the rows in your table to increase to allow the full value of the record cells to be displayed. If the _Enable Word Wrap_ is set to false, an _ellipsis ..._ will display at the end of a cell where the contents are wider than the space available to the column.

<a name="read-only"></a>

### Read Only

Here you can choose whether or not the users of this grid will have the ability to edit or delete records in this table. If the _Read-Only_ value is set to _True_ then the _Edit_ and _Delete_ icons will be _unavailable_ to the user.

<a name="relationships-section"></a>

## Relationships Section

The _Relationships_ section allows you to define relationships between the primary table to which these properties apply and the other tables to which you have access.

<a name="add-relationship"></a>

### Add Relationship

When you click on the _Add Relationship_ button a window pops up that expands step-by-step as you explain the relationship through the various drop-down lists.

<a name="source-column"></a>

-   **Source Column** &mdash; The _Source Column_ drop-down allows you to choose from the columns in the primary table to which this _Properties_ page belongs.

<a name="related-table"></a>

-   **Related Table** &mdash; The _Related Table_ allows you to choose from the other tables in your collection of tables.

<a name="related-column"></a>

-   **Related Column** &mdash; The _Related Column_ drop-down allows you to choose from the columns in the related table you have selected.

<a name="relationship-type"></a>

-   **Relationship Type** &mdash; The _Relationship Type_ allows you to choose how a selected table relates to your primary table by their respective _Related_ and _Source_ columns.

<a name="has-many"></a>

-   **Has Many** &mdash; Does the _Related Table_ with _Has Many_ relationships have multiple records that store the _Source Column_ value of your table in its _Related Column_?

<a name="belongs-to"></a>

#### Belongs To

-   Does your primary table have a _Related Column_ that is storing a value of a _Source Column_ that _Belongs To_ the _Related Table_ you selected?.

<a name="forms-section"></a>

## Forms Section

The _Forms_ section provides a way for you to inject form options into your table actions.

-   One use case is to generate a form for fields within your table that may have business logic associated with them.

    -   For example, You might like to make available a _Hire Form_ only when an employee record has a _Status_ such as _Candidate_ in the _Employees_ table.

-   Another use case is to display a form for a table with _Has Many_ relationships to the selected table.

    -   For example, You might like to add or edit one or more records in the related _Emergency Contact_ table through the _Manage Emergency Contacts_ Form from the _Employees_ table.

Clicking the _Add Form_ button opens up a multi-section _Create Form_ page.

<a name="create-form"></a>

### Create Form

<a name="details"></a>

#### Details

-   In the first section, _Details_, you can name and describe the form that you are creating.

<a name="access"></a>

#### Access

-   In the second section, _Access_, you have a way to add business logic based on the value of a selected column in your table.

<a name="design"></a>

#### Design

The third section, _Design_, provides a simple yet powerful design tool with the flexibility for you to specify the targeted information you want to gather. It also gives you the ability to logically group this targeted information, across multiple tables, by using the _Add Section_ button.

-   **Table** &mdash; This select box lets you select the table you want to fill.

    -   In one use case, you might want to select the current table to fill in columns that you have hidden in your table details.

    -   In another use case, you could select a different table you want to have as a collection point for additional data that is related to a specific record in your primary table.

-   **Section Title** &mdash; This gives you the ability to logically label this section of your form.

-   **Use Two Column Layout** &mdash; This toggle provides you with twice the data-gathering capacity in the same amount of form space.

-   **Edit Existing Records** &mdash; This toggle gives you the ability to chose between whether a user is entering new data or editing data that already exists in the system

-   **Allow Multiple Insert** &mdash; This toggle lets you offer the power of _Has Many_ relationships, to your end-users, at their discretion, on a record by record level.

-   **Fields in Section** &mdash; This "Drag and Drop" design box, in conjunction with the _Available Columns_ list, gives you the ability to select, order and arrange the columns you want to show to the end-users of this form.

<a name="column-properties-section"></a>

## Column Properties Section

The _Column Properties_ section empowers you to design the column-level data definitions for your table.

<a name="add-column"></a>

### Add Column

Clicking the _Add Column_ button will open a dynamic _Add Column_ dialog box with the power to define the data of your new column, based on the _Type_ of the column you select.

<a name="default-column-definition-and-display-options"></a>

#### Default Column Definition and Display Options

In the top 4 definitions, you can name and configure the display features of your new column

-   **Name** &mdash; This is the identifying label that you want to use to reference this column in this table.

-   **Friendly Name** &mdash; This is the end-user focused label that you want to display for this column.

-   **Alignment** &mdash; This select box allows you to tell how you want the orientation of the cell data for this column to be displayed.

-   **Sequence** &mdash; This select box gives you the power to set the order in which you want to display this column.

<a name="type-based-column-definitions"></a>

#### Type-Based Column Definitions

The _Type_ options are _Standard_, _Reference_ and _Calculated_. Each of these _Types_ has its own set of definition options that dynamically displays depending on which _Type_ you select.

<a name="standard-type-definition-options"></a>

#### Standard-Type Definition Options

-   **Column Type** &mdash; This drop-down allows you to set the type of data that you want to enforce in this column.

-   **Column is nullable** &mdash; This toggle gives you the power to tell whether or not this column can have, literally, nothing in it.

-   **Column is unique** &mdash; This toggle lets you tell whether or not to allow a value to exist more than once in this column.

<a name="reference-type-definition-options"></a>

#### Reference-Type Definition Options

<a name="table"></a>

-   **Table** &mdash; This select-box allows you to tell which table to use to get the data you want it to display in this column.

<a name="column"></a>

-   **Column** &mdash; This select box lets your tell which column has the data, from the selected reference table, that you want to use to fill this column.

<a name="column-is-nullable"></a>

-   **Column is nullable** &mdash; This toggle gives you the power to tell whether or not this column can have, literally, nothing in it.

<a name="calculated-type-definition-options"></a>

#### Calculated-Type Definition Options

-   **Expression** &mdash; This code box lets you use [MySQL Functions](https://www.w3schools.com/sql/sql_ref_mysql.asp) to create the calculation statement, that results in a single "scalar value", to return for display in this column.

<a name="tags-section"></a>

## Tags Section

The _Tags_ section lets you add searchable words to your table. For example, if you wanted to find the Employees table, you might add the _Tag_ _ADMIN_ followed by the _Enter_ key. After that, you could add the _Tag_ _HUMAN RESOURCES_ followed by the _Enter_ key. This would provide your table with a searchable set of _Tags_.