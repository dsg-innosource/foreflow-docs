
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

Here you will find a place to upload a data file to populate this table with data and map the columns from that data file to the columns in the table.

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

The Relationships section allows you to define relationships between tables.

## Forms



## Columns


## Tags








