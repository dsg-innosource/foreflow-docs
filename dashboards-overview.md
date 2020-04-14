# Dashboards Overview

Dashboards are user defined visualization tools which allow users to create, display, and analyze metrics and data in their foreflow instance.

You can see existing Dashboards to which you have access by clicking the "Dashboards" item in the menu. These dashboards are listed in a sortable grid. If you have Administrator rights, you will see an Actions column that contains icons for editing or deleting a dashboard, and a button to add a new dashboard.

## Creating a Dashboard

Clicking the "Add Dashboard" button on the Dashboards page will present a dialogue where you can specify the name, table, and a description for your Dashboard. Once a dashboard has been created, you can click the "edit" icon for the newly created dashboard, and begin adding visualizations to your dashboard.

## Adding Visualizations

When viewing a Dashboard, there is a button to "Edit" the Dashboard. Clicking this button will allow you to modify the name and description of the dashboard. While the Dashboard is in "edit" mode, you will also be able to modify the visualizations that are attached to the Dashboard. You can add a new visualization by clicking the "Add Visualization" button.

## Visualization Types

### List Box

The List Box visualization is used to parameterize your dashboard. It provides a distinct list of values from the column to which the list box is configured. Selecting values from a list box will filter the other visualizations on the dashboard so that they only display data for the selected values.

For example, imagine you had a dashboard that displayed a list box of Customer Name's, and a bar chat that displayed the sum of Sales by Customer. If you were to select "Customer A" in the List Box, the Bar Chart would then only display Sales from "Customer A".

### Bar Chart

The Bar Chart visualization is used to display a bar chart for a specific metric. A Bar Chart is configured to show the results of an expression aggregated and displayed a specific dimension. Bar charts are best suited to compare metrics between different groups.

### Line Chart

The Line Chart visualization is used to display a line chart for a specific metric. A Line Chart is configured to show the results of an expression aggregated and displayed a specific dimension. Line charts are best suited to display changes over time.

### Pie Chart

The Pie Chart visualization is used to display a pie chart for a specific metric. A Pie Chart is configured to show the results of an expression for a specific dimension. Pie charts are best suited to display parts of a whole.

### Card

The Card visualization is used to display a scalar value that is based on the aggregation of an expression.
