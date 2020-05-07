# System Events

-   [Introduction](#introduction)
-   [Events Captured](#events-captured)
-   [Accessing Event Data](#accessing-event-data)

<a name="introduction"></a>

## Introduction

To better understand how users interact with the system, certain actions will trigger a _System Event_. These events are recorded in a table for reporting, analytical, or other purposes.

<a name="events-captured"></a>

## Events Captured

The following actions trigger a _System Event_:
-   Logging into the system
-   Resetting a password
-   Accessing a Table
-   Accessing a Dataset
-   Accessing a Dashboard

Each action may record different information. The following information is always collected:
-   The _User_ or _Api Key_ used to access or perform the action
-   The IP Address the actions came from
-   References to the accessed entity
-   Web browser information

<a name="accessing-event-data"></a>

## Accessing Entries

The system event log can be displayed by querying against the `system_events` table either in a _Dataset_ or a _JasperReport_.