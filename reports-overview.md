# Reports Overview

-   [Introduction](#introduction)
-   [Creating Reports](#creating-reports)
-   [Running Reports](#running-reports)

<a name="introduction"></a>

## Introduction

You can see existing Reports to which you have access by clicking the Reports item in the menu. These reports are listed in a sortable grid. If you have Administrator rights, you will see an Actions column that contains icons for editing or deleting a report, and a button to add a new report.

<a name="creating-reports"></a>

## Creating Reports

To add a new report, click the _Add Report_ button. This will open a dialogue where you can upload a JasperReport. You can choose to upload either a single `.jrxml` file, or a `.zip` archive containing the report, as well as any assets (subreports, images, etc) that are required by the report.

Once the report has been uploaded, if the report contains any parameters, you will be presented with a dialogue to set the datatype for each parameter in the report. Depending on the selected datatype, foreflow will present a different input type when the report is run. For example, if you have a report with a date parameter, you should set the type to _date_. This will instruct foreflow to provide a date-chooser input when running the report.

After setting up datatypes for each of the parameters in the report, you can also choose a database connection for the report. By default, the report will run against the foreflow system database, but you can configure additional [connections](/{{version}}/connections-overview) on the Connections page.

Once the database connection has been set, you can click the _Save_ button to save the report in Foreflow.

<a name="running-reports"></a>

## Running Reports

To run a report, you can click the _Run_ icon for the report you would like to run. This will present a dialogue where you can specify the parameters for the report, as well as an export type for the report. Once you have provided the report parameters and an export type, you can click the _Run_ button to begin processing the report. When the report has been rendered, the dialogue will display a _Download_ button which can be clicked to download a copy of the rendered report.
