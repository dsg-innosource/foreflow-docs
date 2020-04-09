
# Table Properties

After selecting a particular table, you can access its properties by clicking the **Properties** button.  The properties page is divided into several sections due to the many options available.  After you set all the properties that you want to be in effect for this table, be sure to click the **Update Table Properties**.

- [Table Properties](#table-properties)
  - [Table Properties Section](#table-properties-section)
    - [Table Friendly Name](#table-friendly-name)
    - [Table Description](#table-description)
    - [Database Table Name](#database-table-name)
    - [Default Number of Rows to Display](#default-number-of-rows-to-display)
    - [Editing Mode](#editing-mode)
    - [Default Sort](#default-sort)
        - [Sort Direction](#sort-direction)
    - [Email Import](#email-import)
    - [Use Client-Side Data Viewer](#use-client-side-data-viewer)
    - [Display Column Chooser](#display-column-chooser)
    - [Allow Data Export](#allow-data-export)
    - [Enable Word Wrap](#enable-word-wrap)
    - [Read Only](#read-only)
  - [Relationships Section](#relationships-section)
  - [Forms Section](#forms-section)
    - [Create Form](#create-form)
        - [Details](#details)
        - [Access](#access)
        - [Design](#design)
  - [Column Properties Section](#column-properties-section)
    - [Add Column](#add-column)
    - [Default Column Definition and Display Options](#default-column-definition-and-display-options)
    - [Type-Based Column Definitions](#type-based-column-definitions)
    - [Standard-Type Definition Options](#standard-type-definition-options)
    - [Reference-Type Definition Options](#reference-type-definition-options)
    - [Calculated-Type Definition Options](#calculated-type-definition-options)
  - [Tags Section](#tags-section)

## Table Properties Section

Here you will find the general table properties:

### Table Friendly Name

This is a user-friendly or business-friendly display name for the table.  This name can be edited by a user with appropriate rights.

### Table Description

This is the explanation of the contents and purpose of this data set.  This description can be edited by a user with appropriate rights.

### Database Table Name
This is the system name of the table.  It cannot be edited.

### Default Number of Rows to Display

This sets the number of rows that will display on each page of the table grid.

[top](#table-properties)

### Editing Mode

Here you will find editing options for users with sufficient rights.

- #### Cell

    When you select the **Cell** option, the user can click on a cell to update it. The active cell is underlined.  

    - To **Accept** the change click the **check mark**.  
    - To **Cancel** the edit click the **X**.
 
- #### Row
 
    When you select the **Row** option, the user must select the edit icon before clicking on a cell to update it. The active cell is underlined.

    - To **Accept** the change click the **check mark**.  
    - To **Cancel** the edit click the **X**.
 
- #### Inline Form
 
    When you select the **Inline Form** option, clicking the edit icon will replace the line with a form for the user to edit. The active cell is underlined.

    - To **Accept** the change click the **check mark**.  
    - To **Cancel** the edit click the **X**.
 
- #### Pop-up Form
 
    When you select the **Pop-up Form** option, clicking the edit icon will open a pop-up window form for the user to edit.

    - To **Accept** the change click the **Save** button.  
    - To **Cancel** the edit click the **Cancel** button.

[top](#table-properties)
 
### Default Sort

This is where you can select one of the columns on the table as your default sorting column.

- #### Sort Direction

    When you select either **Ascending** or **Descending** this direction is applied to the **Default Sort** column that you have selected.

[top](#table-properties)

### Email Import

Here you will be configuring a way to either append or replace data in your table by utilizing an email attachment.  When you click on the **Configure Email Import** button a pop up will appear which contains an interactive file upload box.  When you either drop or select a data file with headers, the following things occur.

- The system generates a **table-specific** email address of this pattern **[Universally_Unique_ID]@[your_*foreflow*_domain].com**.  You will need to use this address to append or replace formatted data in your table

- The system attempts to match the headers on that formatted data file to the columns in your table.  After this the system makes an interface available which allows you to adjust those matches that id cannot match on its own.

- You are then asked to choose whether you want this formatted file to **Append To** or to **Replace** the data in your table.

When you attach a formatted data file to an email to the generated address, the system will either append or replace the data in your table with the data in your file, depending on the action you configured.

[top](#table-properties)

### Use Client-Side Data Viewer

This is where you can choose to display your table in either a server-paged data grid or the Client-Side Data Viewer.  While the Client-Side Data Viewer has greater functionality associated with it, the quantity of the data is significantly limited (10,000 rows) due to the memory constraints of your Client-Side computer and the web browser you are using.  This value defaults to **False**.

[top](#table-properties)

### Display Column Chooser

Here you can choose whether or not the users of this grid will have the ability to see and choose columns to display for this data table.  If the **Display Column Chooser** is set to **False** then the **Column Chooser** icon will be **unavailable** to the user.  The only columns that are displayed will be those whose property **IS SHOWN BY DEFAULT** is checked in the **Column Properties** setup below.

[top](#table-properties)

### Allow Data Export

Here you can choose whether or not the users of this grid will have the ability to export the data in this table.  If the **Allow Data Export** is set to **False** then the **Export Data** icon will be **unavailable** to the user.

[top](#table-properties)

### Enable Word Wrap

This is where you can choose to allow the height of the rows in your table to increase to allow the full value of the record cells to be displayed.  If the **Enable Word Wrap** is set to false, an **ellipsis ...** will display at the end of a cell where the contents are wider than the space available to the column.

[top](#table-properties)

### Read Only

Here you can choose whether or not the users of this grid will have the ability to edit or delete records in this table.  If the **Read-Only** value is set to **True** then the **Edit** and **Delete** icons will be **unavailable** to the user.

[top](#table-properties)

## Relationships Section

The **Relationships** section allows you to define relationships between the primary table to which these properties apply and the other tables to which you have access.

[top](#table-properties)

### Add Relationship

When you click on the **Add Relationship** button a window pops up that expands step-by-step as you explain the relationship through the various drop-down lists.

- #### Source Column

    The **Source Column** drop-down allows you to choose from the columns in the primary table to which this **Properties** page belongs.

- #### Related Table

    The **Related Table** allows you to choose from the other tables in your collection of tables.

- #### Related Column

    The **Related Column** drop-down allows you to choose from the columns in the related table you have selected.

- #### Relationship Type

    The **Relationship Type** allows you to choose how a selected table relates to your primary table by their respective **Related** and **Source** columns.  

    - #### Has Many

        - Does the **Related Table** with a **Has Many** relationship have multiple records that store the **Source Column** value of your table in its **Related Column**? 

    - #### Belongs To    

    - Does your primary table have a **Related Column** that is storing a value of a **Source Column** that **Belongs To** the **Related Table** you selected?.

[top](#table-properties)

## Forms Section

The **Forms** section provides a way for you to inject form options into your table actions.  

- One use case is to generate a form for fields within your table that may have business logic associated with them.  

    - For example, You might like to make available a **Hire Form** only when an employee record has a **Status** such as **Candidate** in the **Employees** table.

- Another use case is to display a form for a table with a **Has Many** relationship to the selected table.  

    - For example, You might like to add or edit one or more records in the related **Emergency Contact** table through the **Manage Emergency Contacts** Form from the **Employees** table.

[top](#table-properties)

Clicking the **Add Form** button opens up a multi-section **Create Form** page.  

### Create Form

### Details
- In the first section, **Details**, you can name and describe the form that you are creating.  

### Access

- In the second section, **Access**, you have a way to add business logic based on the value of a selected column in your table.

[top](#table-properties)

### Design

- The third section, **Design**, provides a simple yet powerful design tool with the flexibility for you to specify the targeted information you want to gather.  It also gives you the ability to logically group this targeted information, across multiple tables, by using the **Add Section** button.

    - The **Table** select box lets you select the table you want to fill.  

        - In one use case, you might want to select the current table to fill in columns that you have hidden in your table details.  
        
        - In another use case, you could select a different table you want to have as a collection point for additional data that is related to a specific record in your primary table.

    - The **Section Title** gives you the ability to logically label this section of your form.

    - The **Use Two Column Layout**  toggle provides you with twice the data-gathering capacity in the same amount of form space.

    - The **Edit Existing Records** toggle gives you section level data security

    - The **Allow Multiple Insert** toggle lets you offer the power of the **Has Many** relationship, to your end-users, at their discretion, on a record by record level.

    - The **Fields in  Section** "Drag and Drop" design box, in conjunction with the **Available Columns** list, gives you the ability to select, order and arrange the columns you want to show to the end-users of this form.

[top](#table-properties)

## Column Properties Section

The **Column Properties** section empowers you to design the column-level data definitions for your table.  

### Add Column

Clicking the **Add Column** button will open a dynamic **Add Column** dialog box with the power to define the data of your new column, based on the **Type** of the column you select.

[top](#table-properties)

#### Default Column Definition and Display Options
In the top 4 definitions, you have the ability to name and configure the display features of your new column

- #### Name

    This is the identifying label that you want to use to reference this column in this table.

- #### Friendly Name

    This is the end-user focused label that you want to display for this column.

- #### Alignment

    This select box allows you to tell how you want the orientation of the cell data for this column to be displayed.

- #### Sequence

    This select box gives you the power to set the order in which you want to display this column.

[top](#table-properties)

 #### Type-Based Column Definitions  

 The **Type** options are **Standard**, **Reference** and **Calculated**.  Each of these **Types** has its own set of definition options that dynamically displays depending on which **Type** you select.

[top](#table-properties)

> #### Standard-Type Definition Options
>
> - #### Column Type
>
>   This drop-down allows you to set the type of data that you want to enforce in this column.
>
> - #### Column is nullable
>
>   This toggle gives you the power to tell whether or not this column can have, literally, nothing in it.
>
> - #### Column is unique
>
>   This toggle lets you tell whether or not to allow a value to exist more than once in this column.
>
>[top](#table-properties)
>
> #### Reference-Type Definition Options
>
> - #### Table
>
>   This select-box allows you to tell which table to use to get the data you want it to display in this column.
>
> - #### Column
>
>   This select box lets your tell which column has the data, from the selected reference table, that you want to use to fill this column.
>
> - #### Column is nullable
>
>   This toggle gives you the power to tell whether or not this column can have, literally, nothing in it.
>
>[top](#table-properties)
>
> #### Calculated-Type Definition Options
>
> - #### Expression
>
>   This code box lets you use **[MySQL Functions](https://www.w3schools.com/sql/sql_ref_mysql.asp)** to create the calculation statement, that results in a single "scalar value", to return for display in this column.


[top](#table-properties)

## Tags Section

The **Tags** section lets you add searchable words to your table.  For example, if you wanted to find the Employees table, you might add the **Tag** *ADMIN* followed by the **Enter** key. After that, you could add the **Tag** *HUMAN RESOURCES* followed by the **Enter** key. This would provide your table with a searchable set of **Tags**.

[top](#table-properties)







