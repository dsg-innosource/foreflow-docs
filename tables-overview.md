# Overview

- [Introduction](#introduction)
- [Table Name](#table-name)
- [Show/Hide Deleted Records](#show-/-hide-deleted-records)
- [Dashboards](#dashboards)
- [Actions](#actions)
- [Import](#import)
- [Properties](#properties)

<a name="introduction"></a>

## Introduction

Once a table is selected,The **Table Header** provides you with some global **Table Management** options which are based on user role and table property configurations. 

<a name="table-name"></a>

- ### Table Name

    The **Table Name** appears is displayed with a **ROW COUNT** and **TAGS** beneath it.

<a name="show-/-hide-deleted-records"></a>

- ### Show/Hide Deleted Records

    If rows have been deleted from the table the **Show/Hide Deleted Records** button appears.

<a name="dashboards"></a>

- ### Dashboards

    If a dashboard has been created for your table, a **Dashboards** button will appear.  When you click on the word **Dashboards** in the button, all the existing dashboards will appear and selecting one will take you to the dashboard you selected.

<a name="actions"></a>

- ### Actions

    If a dashboard has been created for your table, a **Actions** button will appear.  When you click on the word **Actions** in the button, all the existing **Actions** will appear and selecting one will take you to the dashboard you selected.

<a name="import"></a>

- ### Import

    When you click on the **Import** button a pop up will appear which contains an interactive file upload box.  When you either drop or select a data file with headers, the following things occur.

    - The system attempts to match the headers on that formatted data file to the columns in your table.  After this the system makes an interface available which allows you to adjust those matches that id cannot match on its own.

    - You are then asked to choose the **Import settings**.  Here you can choose whether you want this formatted file to **Append this file's data to the Customers table** or to **Replace the data in the Customers table with this file's data**.  If you choose the **Replace** option, a **Replace Data** pop-up will appear with a dialog box making sure you really want to replace the data. Clicking **Yes** will confirm that is what you want to do.

    When you attach a formatted data file to an email to the generated address, the system will either append or replace the data in your table with the data in your file, depending on the action you configured.

<a name="properties"></a>

- ### Properties

    Click the Properties button to modify a new or existing table.  You will be taken to the [Properties](table-properties) page, where you can modify table properties and add or remove table columns.

