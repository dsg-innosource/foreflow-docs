# Table Columns

-   [Introduction](#introduction)
-   [Add Column](#add-column)
-   [Default Column Definition and Display Options](#default-column-definition-and-display-options)
-   [Type-Based Column Definitions](#type-based-column-definitions)
-   [Standard-Type Definition Options](#standard-type-definition-options)
-   [Reference-Type Definition Options](#reference-type-definition-options)
-   [Calculated-Type Definition Options](#calculated-type-definition-options)
-   [Custom Column Types](#custom-column-types)

<a name="introduction"></a>

## Introduction

> This page was extraced from the [Table Properties](/{{version}}/tables-properties) page.

The _Columns_ tab empowers you to design the column-level data definitions for your table.

<a name="add-column"></a>

## Add Column

Clicking the _Add Column_ button will open a dynamic _Add Column_ dialog box with the power to define the data of your new column, based on the _Type_ of the column you select.

<a name="default-column-definition-and-display-options"></a>

### Default Column Definition and Display Options

In the top 4 definitions, you can name and configure the display features of your new column

-   **Name** &mdash; This is the identifying label that you want to use to reference this column in this table.

-   **Friendly Name** &mdash; This is the end-user focused label that you want to display for this column.

-   **Alignment** &mdash; This select box allows you to tell how you want the orientation of the cell data for this column to be displayed.

-   **Sequence** &mdash; This select box gives you the power to set the order in which you want to display this column.

<a name="type-based-column-definitions"></a>

### Type-Based Column Definitions

The _Type_ options are _Standard_, _Reference_ and _Calculated_. Each of these _Types_ has its own set of definition options that dynamically displays depending on which _Type_ you select.

<a name="standard-type-definition-options"></a>

### Standard-Type Definition Options

-   **Column Type** &mdash; This drop-down allows you to set the type of data that you want to enforce in this column.

-   **Column is nullable** &mdash; This toggle gives you the power to tell whether or not this column can have, literally, nothing in it.

-   **Column is unique** &mdash; This toggle lets you tell whether or not to allow a value to exist more than once in this column.

<a name="reference-type-definition-options"></a>

### Reference-Type Definition Options

<a name="table"></a>

-   **Table** &mdash; This select-box allows you to tell which table to use to get the data you want it to display in this column.

<a name="column"></a>

-   **Column** &mdash; This select box lets your tell which column has the data, from the selected reference table, that you want to use to fill this column.

<a name="column-is-nullable"></a>

-   **Column is nullable** &mdash; This toggle gives you the power to tell whether or not this column can have, literally, nothing in it.

<a name="calculated-type-definition-options"></a>

### Calculated-Type Definition Options

-   **Expression** &mdash; This code box lets you use [MySQL Functions](https://www.w3schools.com/sql/sql_ref_mysql.asp) to create the calculation statement, that results in a single "scalar value", to return for display in this column.

<a name="custom-column-types"></a>

### Custom Column Types

Custom column types are those that are not a database constraint but one custom created for foreflow use.

-   **URL** &mdash; This column type creates a string column that accepts a valid URL. When displaying this column in a grid the URL is rendered so that it is clickable.
