# Dataset Overview

-   [Introduction](#introduction)
-   [API Access](#api-access)
-   [Creating Datasets](#creating-datasets)
-   [Editing Datasets](#editing-datasets)
-   [Dataset Properties](#dataset-properties)
-   [Column Properties](#column-properties)

<a name="introduction"></a>

## Introduction

Datasets are used to provide different views of data that exists in foreflow, or another system that is connected to foreflow. Datasets execute raw SQL against a specific database connection, and provide the results in a sortable grid.

<a name="api-access"></a>

## API Access

When a dataset has API Access enabled, the dataset will become accessible via foreflow's API. You can read more about API access in the [API Documentation](/docs/{{version}}/api).

<a name="creating-datasets"></a>

## Creating Datasets

You can see existing Datasets to which you have access by clicking the Datasets item in the menu. These Datasets are listed in a sortable grid. If you have Administrator rights, you will see an Actions column that contains icons for editing or deleting a report, and a button to add a new report.

To add a new dataset, click the _Add Dataset_ button. This will open a dialogue where you can provide a name and description for your dataset. You will also be able to specify which database connection the dataset should be run against.

Once the dataset has been created, it will appear in the grid.

<a name="editing-datasets"></a>

## Editing Datasets

To edit a Dataset, you will need to locate the dataset in the Datasets grid, and click the edit icon. This will take you to a page where you can modify the dataset.

<a name="dataset-properties"></a>

## Dataset Properties

In some cases, the results of a dataset may include columns that contain long text data. In this cases, it may be helpful to enable _word wrap_ on the dataset, which will instruct foreflow to wrap text on all columns of the dataset.

<a name="column-properties"></a>

## Column Properties

Once a dataset has a valid statement, you will be able to preview all of the columns that are returned from the dataset. In some cases, you may want to override the text alignment for a particular column, which you are able to do in the Column Properties panel.
