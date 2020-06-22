# Report Parameters

- [Report Parameters](#report-parameters)
  - [Introduction](#introduction)
  - [Parameter Types](#parameter-types)
    - [String](#string)
    - [Integer](#integer)
    - [Date](#date)
    - [Date & Time](#date--time)
    - [List from Foreflow Table Column](#list-from-foreflow-table-column)
    - [User Email Address](#user-email-address)

<a name="introduction"></a>

## Introduction

Report parameters are used to filter data within a report.

<a name="parameter-types"></a>

## Parameter Types

<a name="string"></a>

### String

The string parameter type allows the user to provide a text string for the parameter. When providing values for a string parameter, foreflow will display a text input.

<a name="integer"></a>

### Integer

The Integer parameter type allows the user to provide an integer for the parameter. When providing values for a string parameter, foreflow will display a numeric input.

<a name="date"></a>

### Date

The Date parameter type allows the user to provide a date for the parameter. When providing values for a Date parameter, foreflow will display a date chooser input.

<a name="date-time"></a>

### Date & Time

The Date & Time parameter type allows the user to provide a timestamp for the parameter. When providing values for a Date & Time parameter, foreflow will display a date and time chooser input.

<a name="list-from-foreflow-table-column"></a>

### List from Foreflow Table Column

The List from Foreflow Table Column parameter type allows the user to provide a value from a Foreflow table. When providing values for a List from Foreflow Table Column parameter, foreflow will display a drop down list of values from the configured column.

<a name="user-email-address"></a>

### User Email Address

The User Email Address parameter type allows for User level filtering within a JasperReport.  When setting up a parameter as a "User Email Address" parameter, foreflow will automatically inject the authenticated user's email address into the report parameter.  This allows the data in the report to be filtered down to only the data to which the user has access.  The only case where a user will be prompted to provide a value for this parameter is if the report is being distributed by foreflow.  