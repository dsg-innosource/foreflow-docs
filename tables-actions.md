# Table Actions

## Table of Contents

-   [Introduction](#introduction)
-   [Existing Actions](#existing-actions)
    -   [Options](#options)
-   [Adding An Action](#adding-an-action)
-   [Action Types](#action-types)
    -   [Task](#task)
    -   [Batch](#batch)
    -   [Package](#package)
    -   [Conditional Row Updates](#conditional-row-updates)

<a name="introduction"></a>

## Introduction

The _Table Actions_ allow you to perform an action on demand or after data has been updated in your table. The available actions are found in the [Action Types](#action-types) section below.

<a name="existing-actions"></a>

## Existing Actions

After _Table Actions_ have been associated with this table they appear as objects under the _Existing Actions_ heading. These _Table Actions_ display information about the configured action.

<a name="options"></a>

### Options

Clicking the _three-dot_ icon provides a list of available options for the corresponding _Table Action_.

-   **Edit** &mdash; Opens the _Action Type_ modal to allow for changes

-   **View** (conditional) &mdash; Navigates to the correseponding [Orchestration](/{{version}}/orchestration-overview) page

-   **Run** (conditional) &mdash; After confirmation, immediately runs the selected action

-   **Remove** &mdash; After confirmation, deletes the configured action

<a name="adding-an-action"></a>

## Adding An Action

To add a new action to the table, select an _Action Type_ from the _Select New Action Type_ dropdown and click _Add Action_. Once you've selected your action and click _Add Action_, a configuration modal should appear corresponding to the selected [Action Type](#action-types).

<a name="action-types"></a>

## Action Types

Several different _Action Types_ are available that can modify columns directly or run a configured [Orchestration](/{{version}}/orchestration-overview) entity.

<a name="task"></a>

### Task

This configuration modal provides a list of _Tasks_ from which you can select.

<a name="batch"></a>

### Batch

This configuration modal provides a list of _Batches_ from which you can select.

<a name="package"></a>

### Package

This configuration modal provides a list of _Packages_ from which you can select.

<a name="conditional-row-updates"></a>

### Conditional Row Updates

This configuration modal provides an interface to create one or multiple conditions in which a column should be updated with a value.

#### Conditional Type

There are two options for this setting:

-   **Match all conditions** &mdash; Requires _ALL_ the conditions defined in the _IF_ section to be true for the _THEN_ action to be executed
-   **Match any conditions** &mdash; Requires _ANY_ the conditions defined in the _IF_ section to be true for the _THEN_ action to be executed

#### _IF_ section

This section provides a column, operator, and value to set for conditions in which the _THEN_ action would be constrained by.

-   **Column** &mdash; Provides a list of columns from the current _Table_ to perform the conditional check on
-   **Operator** &mdash; Provides a list of available comparison operators. This operator will be used to evaluate the current value in the _Column_ specified against the comparison _Value_.
-   **Value** &mdash; A input to specify a comparison value. This value is compared against the current value in the column specified using the _Operator_

#### _THEN_ section

This section allows the user to specify what should happend if the conditions specified occur.

-   **Column** &mdash; Provides a list of columns from the current _Table_ to set the _Value_
-   **Value** &mdash; An input to specify the value that should be set on the _Column_
