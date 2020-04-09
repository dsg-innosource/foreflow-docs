
# Table Properties 

After selecting a particular table, you can access its properties by clicking the **Properties** button.  The properties page is divided into several sections due to the many options available.  After you set all the properties that you want to be in effect for this table, be sure to click the **Update Table Properties**.

## Table Properties

Here you will find the general table properties:

### Friendly Name

This is a user-friendly or business-friendly display name for the table.  This name can be edited by a user with appropriate rights.

### Description

This is the explanation of the contents and purpose of this data set.  This description can be edited by a user with appropriate rights.

### Database Table Name
This is the system name of the table which foreflow creates when the table is created.  It cannot be edited.

### Default Number of Rows to Display

This sets the number of rows that will display on each page of the table grid.

### Editing Mode

Here you will find a number of options that foreflow has built in for a user with appropriate rights to edit the data in your tables.

- #### Cell

    When you select the **Cell** option, the user can click on a cell to update it. Foreflow designates which cell is active by underlining it.  

    - To **Accept** the change click the **check mark**.  
    - To **Cancel** the edit click the **X**.
 
- #### Row
 
    When you select the **Row** option, the user must select the edit icon before clicking on a cell to update it.

    - To **Accept** the change click the **check mark**.  
    - To **Cancel** the edit click the **X**.
 
- #### Inline Form
 
    When you select the **Inline Form** option, when the user selects a record for editing, foreflow will replace the line with a form for the user to edit.

    - To **Accept** the change click the **check mark**.  
    - To **Cancel** the edit click the **X**.
 
- #### Pop-up Form
 
    When you select the **Pop-up Form** option, when the user selects a record for editing, foreflow will open a pop-up window form for the user to edit.

    - To **Accept** the change click the **SAVE** button.  
    - To **Cancel** the edit click the **CANCEL** button.
 
### Default Sort

This is where you can select one of the columns on the table as your default sorting column.

- #### Sort Direction

    When you select either **Ascending** or **Descending** foreflow applies this direction to the **Default Sort** column that you have selected.

### Email Import

Here you will be configuring a way to either append or replace data in your table by means of an email attachment.  When you click on the **Configure Email Import** button a pop up will appear which contains an interactive file upload box.  When you either drop or select a data file with headers a number of things occur.

- Foreflow generates a **table-specific** email address of this pattern **[Universally_Unique_ID]@[your_Foreflow_domain].com**.  You will need to use this address to append or replace formatted data in your table

- Foreflow attempts to match the headers on that formatted data file to the columns in your table.  Foreflow makes an interface available which allows you to adjust those matches that foreflow cannot match on its own.

- Foreflow asks you to choose whether you want this formatted file to **Append To** or to **Replace** the data in your table.

When you attach a formatted data file to an email to the foreflow generated address, foreflow will either append of replace the data in your table with the data in your file, depending on the action you configured.

### Use Client Side Data Viewer

This is where you can choose to display your table in either a server-paged data grid or the Client Side Data Viewer.  While the Client Side Data Viewer has greater functionality associated with it, the quantity of the data is significantly limited (10,000 rows) due to the memory constraints of your Client-Side computer and the web browser you are using.  Because of these constraints foreflow defaults this value to **False**.

### Display Column Chooser

Here you can choose whether or not the users of this grid will have the ability to see and choose columns to display for this data table.  If the **Display Column Chooser** is set to **False** then the **Column Chooser** icon will be **unavailable** to the user.  In this case foreflow will only serve up the columns who's property **IS SHOWN BY DEFAULT** is checked in the **Column Properties** setup below.

### Allow Data Export

Here you can choose whether or not the users of this grid will have the ability to export the data in this table.  If the **Allow Data Export** is set to **False** then the **Export Data** icon will be **unavailable** to the user.

### Enable Word Wrap

This is where you can choose to allow the height of the rows in your table to increase to allow the full value of the record cells to be displayed.  If the **Enable Word Wrap** is set to false, an **elipsis ...** will display at the end of a cell where the contents are wider than the space available to the column.

### Read Only

Here you can choose whether or not the users of this grid will have the ability to edit or delete records in this table.  If the **Read Only** value is set to **True** then the **Edit** and **Delete** icons will be **unavailable** to the user.


## Relationships

The **Relationships** section allows you to define relationships between the primary table to which these properties apply and the other tables to which you have access.

When you click on the **Add Relationships** button a window pops up that expands step-by-step as you explain the relationship through the various drop down lists.

![tables-properties-add-relationships](img/tables-properties-add-relationships.png)

The **Source Column** drop down allows you to choose from the columns in the primary table to which this **Properties** page belongs.

The **Related Table** allows you to choose from the other tables in your collection of tables.

The **Related Column** drop down allows you to choose from the columns in the related table you have selected.

The **Relationship Type** allows you to choose how a selected table relates to your primary table by their respective **RELATED** and **Source** columns.  

- Does the selected table with a **Has Many** relationship have multiple records that store the **SOURCE COLUMN** value of your table in its **RELATED COLUMN**? 

- Does your primary table have a **RELATED COLUMN** that is storing a value of a **SOURCE COLUMN** that **Belongs To** the **RELATED TABLE** you selected?.

## Forms

The **Forms** section provides a way for you inject form options into your table actions.  

- One usecase is to generate a form for fields within your table that may have business logic associated with them.  
    - For example: You might like to make available a **Hire Form** only when an employee record has a **Status** such as **Candidate** in the **Employees** table.

- Another usecase is to display a form for a table with a **Has Many** relationship to the selected table.  
    - For example: You might like to add or edit one or more records in the related **Emergency Contact** table by means of the **Manage Emergency Contacts** Form from the **Employees** table.

## Columns


## Tags








