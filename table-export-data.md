# Exporting Data from a Table

-   [Introduction](#introduction)

<a name="introduction"></a>

## Introduction

You may want to download data from a foreflow table to analyze it in Excel or use it in another application or system. To do this, use the _Export Data_ feature.

Navigate to the table from which you want to export data, and click on the _Export Data_ icon:

_(image coming soon)_

The export process is different depending on the _Table Properties_ setup. If the _Use Client Side Data Viewer_ setting for the table from which you are exporting data is set to _False_, you will then see a dialog box appear with _Queue Export_ and _Cancel_ options. When you select _Queue Export_, foreflow schedules a _Task_ that exports the data. When foreflow completes the export, you will receive an email with a _Download File_ link. Clicking this will download your data in .xlsx format.

If the _Use Client Side Data Viewer_ setting for the table from which you are exporting data is set to _True_, the data you've selected will download immediately in .xlsx format.
