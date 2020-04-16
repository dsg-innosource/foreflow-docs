# Overview

- [Introduction](#introduction)
- [Table Name](#table-name)
- [Show/Hide Deleted Records](#show-/-hide-deleted-records)
- [Dashboards](#dashboards)
- [Run Actions](#run-actions)
- [Import](#import)
- [Properties](#properties)

<a name="introduction"></a>

## Introduction

Once a table is selected, the _Table Header_ provides you with some global _Table Management_ options which are based on user role and table property configurations. 

<a name="table-name"></a>

## Table Name

The _Table Name_ appears is displayed with a _ROW COUNT_ and _TAGS_ beneath it.

<a name="show-/-hide-deleted-records"></a>

## Show/Hide Deleted Records

If rows have been deleted from the table the _Show/Hide Deleted Records_ button appears.

<a name="dashboards"></a>

## Dashboards

If a dashboard has been created for your table, a _Dashboards_ button will appear.  When you click on the word _Dashboards_ in the button, all the existing dashboards will appear and selecting one will take you to the dashboard you selected.

<a name="run-actions"></a>

## Run Actions

If _Task, Batch, or Package Actions_ have been created in the  _[Properties](tables-properties#table-actions)_ page for your table, a _Run Actions_ button will appear.  When you click on the word _Run Actions_ in the button, all the existing _Actions_ will appear and selecting one will take you to the dashboard you selected.  When you click on one of those actions a confirmation dialog box appears to be sure that you what to run that action.  Clicking _Run_ will run the selected action.

<a name="import"></a>

## Import

When you click on the _Import_ button a pop up will appear which contains an interactive file upload box.  When you either drop or select a data file with headers, the following things occur.

- The system attempts to match the headers on that formatted data file to the columns in your table.  After this, the system makes an interface available which allows you to adjust those matches that id cannot match on its own.

- You are then asked to choose the _Import settings_.  Here you can choose whether you want this formatted file to _Append this file's data to the Customers table_ or to _Replace the data in the Customers table with this file's data_.  If you choose the _Replace_ option, a _Replace Data_ pop-up will appear with a dialog box making sure you really want to replace the data. Clicking _Yes_ will confirm that this is what you want to do.

When you attach a formatted data file to an email to the generated address, the system will either append or replace the data in your table with the data in your file, depending on the action you configured.

<a name="properties"></a>

## Properties

Click the Properties button to modify a new or existing table.  You will be taken to the [Properties](table-properties) page, where you can modify table properties and add or remove table columns.