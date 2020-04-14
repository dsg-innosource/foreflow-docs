# Report Distribution

Foreflow can be configured to distribute reports according to a schedule.  Report distribution requires access to the following features in foreflow:

- Reports
- Datasets
- Tasks

## Creating a Report Distribution Dataset

In order to distribute a report, you will need to create a Dataset in the system that contains any parameters used by the report, as well as a column for the recipient's email address.  Each row that is returned by the dataset represents an email being sent, with corresponding parameters that will be provided to the report at run time.

## Creating a Report Distribution Task

To create a Report Distribution Task, you will need to have already created the Report, and the Report Distribution Dataset.

On the Tasks page, you can create a new task by clicking the "Add Task" button.  You will be presented with a dialogue where you can specify a name and description for the task.  To set this task up as a Report Distribution Task, you will select "JasperReports" from the Task Group dropdown, and "JasperReport Distribution" from the Task Type dropdown.  Selecting these two items will expand the form for further configuration.

You will next select the JasperReport that you would like to distribute, as well as the Dataset that will be used to control the parameters and recipient list for the distribution.

Once a report and dataset have been selected, you will be able to configure the parameter mapping and export type for the distribution task. 