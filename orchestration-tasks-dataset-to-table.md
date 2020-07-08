# Orchestration Tasks &mdash; Dataset to Table

-   [Introduction](#introduction)
-   [Dataset Column Names](#dataset-column-names)
-   [Creating a Dataset to Table Task](#creating-a-dataset-to-table-task)
-   [Syncing Dataset Changes](#syncing-dataset-changes)

<a name="introduction"></a>

## Introduction

Foreflow can be configured to sync data between a Dataset and a Table.  

<a name="dataset-column-names"></a>

## Dataset Column Names

Because of how foreflow handles internal metadata tracking, certain column names are not allowed on a Dataset that is set up to sync its data to a table.  If the following column names exist in a Dataset, this type of task cannot be created:

- id
- created_at
- updated_at
- deleted_at
- created_by
- last_updated_by

This limitation can be overcome by providing an alias for a column with one of the above names:

```sql
    select
        id as employee_id
        ,created_at as record_created_at

    from
        employees;
```

<a name="creating-a-dataset-to-table-task"></a>

## Creating a Dataset to Table Task

To create a Dataset to Table Task, you will need to have already created the Dataset.

On the Tasks page, you can create a new task by clicking the "Add Task" button. You will be presented with a dialogue where you can specify a name and description for the task. To set this task up as a Dataset to Table Task, you will select "Datasets" from the Task Group dropdown, and "Dataset to Table" from the Task Type dropdown. Selecting these two items will expand the form for further configuration.

You will next select the Dataset that you would like to sync to a Table, and provide a name for the destination Table.

<a name="syncing-dataset-changes"></a>

## Syncing Dataset Changes

Foreflow will automatically sync the structure of the Dataset to the destination table.  For example, if a Dataset to Table task already exists for a particular Dataset, if a column is added to the Dataset, that change will be reflected in the Table the next time the task is executed.

