# Talend Tasks

-   [Introduction](#introduction)
-   [Error Handling](#error-handling)


<a name="introduction"></a>

## Introduction

<a name="error-handling"></a>

## Error Handling

Foreflow is set up in such a way to be able to receive error output from Talend processes. In order to have errors from a Talend process bubble up to foreflow, you will need to add a few components to the Talend job.

![talend-errors](/{{version}}/img/talend-errors.png)

You will first need a tLogCatcher component, which needs to be configured to catch Java exceptions, tDie, and tWarn.

![talend-catch-errors](/{{version}}/img/talend-catch-errors.png)

The output from the tLogCatcher component needs to be output to a tMap component.

![talend-errors-tmap](/{{version}}/img/talend-errors-tmap.png)

The tMap output needs to be sent to a tLogRow component.

![talend-errors-tlogrow](/{{version}}/img/talend-errors-tlogrow.png)
