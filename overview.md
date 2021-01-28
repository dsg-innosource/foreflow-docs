# foreflow version 2.x

Here you can find out what's new and what used to be new but is no longer.

--- 

## Version 2.4

**Sunday, May 17th, 2020**

### New Features & Improvements

- foreflow can now be configured to sync data between a Dataset and a Table using the new "[Dataset to Table](/{{version}}/orchestration-tasks-dataset-to-table)" task type.

- foreflow now supports [Postgres database connections](/{{version}}/connections-overview#postgres)

- Users can now see the details of currently running Orchestrate tasks

- foreflow now allows [Conditional Table Actions](/{{version}}/tables-actions#conditional-row-updates)

- foreflow now supports [Active Directory integration](/{{version}}/users-active-directory)

- Users can now apply [Column Validation Rules](/{{version}}/tables-properties#column-validation-section) to inserted or updated table records

- Users can now resize the columns on the Dataset listing page

### Bug Fixes

- Resolved an issue where Reference Column record ID's were being displayed in Dashboard visualizations instead of the Reference Column value

- Resolved an issue where Table Actions were not firing under certain conditions

