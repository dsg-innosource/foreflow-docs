# System Events Overview

-   [Introduction](#introduction)
-   [Events Captured](#events-captured)
-   [Accessing Event Data](#accessing-event-data)

<a name="introduction"></a>

## Introduction

To better understand how users interact with the system, certain actions will trigger a log to be created.

<a name="events-captured"></a>

## Events Captured

The data the system logs includes:

-   The user or api key used to access the system
-   The ip address of the user
-   Details about the specific event

The events that are logged are:

-   Login
-   Password Resets
-   Table Access
-   Dataset Access
-   Dashboard Access

<a name="accessing-event-data"></a>

## Accessing Event Data

The system event log can be displayed by querying against the _system_events_ table either in a dataset or a JasperReport.