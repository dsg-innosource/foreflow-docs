#Connections Overview

-   [Introduction](#introduction)
-   [Connection Types](#connection-types)
    -   [Harvest](#harvest)
    -   [Forecast](#forecast)
    -   [MySql](#mysql)
    -   [Postgres](#postgres)

<a name="introduction"></a>

## Introduction

Foreflow allows users to configure connections to other databases, and services. An internal foreflow database connection is already configured and available for use.

<a name="connection-types"></a>

## Connection Types

All connection types allow you to specify a _Name_ and a _Description_ for the connection.

<a name="harvest"></a>

### Harvest

> **Note:** In order to connect to a Harvest account, you'll need to set up a Personal Access Token in your Harvest account. Visit the [Harvest Developer Tools](https://id.getharvest.com/developers) page to set one up.
>
> This Personal Access Token will need to be created by a user with Administrative privileges on your Harvest account.

Once creating the connection a number of [Tasks](/{{version}}/orchestration-overview#tasks) and [Tables](/{{version}}/tables-overview) are created automatically.

The following _Tables_ are created for the Harvest connection:

-   **Client Contacts** &mdash; author_harvest_client_contacts
-   **Clients** &mdash; author_harvest_clients
-   **Projects** &mdash; author_harvest_projects
-   **Tasks** &mdash; author_harvest_tasks
-   **Time Entries** &mdash; author_harvest_time_entries
-   **Users** &mdash; author_harvest_users

The following _Tasks_ are created for the Harvest connection:

-   Load Harvest Client Contacts
-   Load Harvest Clients
-   Load Harvest Projects
-   Load Harvest Tasks
-   Load Harvest Time Entries
-   Load Harvest Users

<a name="forecast"></a>

### Forecast

> **Note:** In order to connect to a Forecast account, you'll need to set up a Personal Access Token in your Forecast account. Visit the [Harvest Developer Tools](https://id.getharvest.com/developers) page to set one up. Be sure to select your Forecast account when copying the Access Token and Account ID.
>
> This Personal Access Token will need to be created by a user with Administrative privileges on your Forecast account.

Once creating the connection a number of [Tasks](/{{version}}/orchestration-overview#tasks) and [Tables](/{{version}}/tables-overview) are created automatically.

The following _Tables_ are created for the Harvest connection:

-   **Assignments** &mdash; author_forecast_assignments
-   **Clients** &mdash; author_forecast_clients
-   **People** &mdash; author_forecast_people
-   **Projects** &mdash; author_forecast_projects

The following _Tasks_ are created for the Harvest connection:

-   Load Forecast Assignments
-   Load Forecast Clients
-   Load Forecast People
-   Load Forecast Projects

<a name="mysql"></a>

### MySql

Creating a [MySql](https://dev.mysql.com/doc/) connection requires entering the following fields:

-   **Host** &mdash; The IP Address of the server you want to connect to
-   **Port** &mdash; The port to use for the connection
-   **Database** &mdash; The name of the database to connect to
-   **Username** &mdash; The username to use for the connection
-   **Password** &mdash; The password to use for the connection

<a name="postgres"></a>

### Postgres

Creating a [Postgres](https://www.postgresql.org/docs/) connection requires entering the following fields:

-   **Host** &mdash; The IP Address of the server you want to connect to
-   **Port** &mdash; The port to use for the connection
-   **Database** &mdash; The name of the database to connect to
-   **Username** &mdash; The username to use for the connection
-   **Password** &mdash; The password to use for the connection
