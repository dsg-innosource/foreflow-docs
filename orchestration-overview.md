# Orchestration Overview

One of the features of foreflow is a scheduling engine.  This scheduling engine is broken down into three entities: Tasks, Batches, and Packages.  Various tasks can be created and organized into Batches and Packages in order to create more complex data loads. 

## Tasks

Tasks are the smallest units of work in the scheduling engine, and have a wide range of functionality. 

### Task Types

#### JasperReport Distribution

The JasperReport Distribution task allows you to distribute a JasperReport to a distribution list. Read more about configuring a JasperReport Distribution task [here](/docs/{{version}}/report_distribution).

#### Shell Script Execution

The Shell Script task allows you to execute a shell script.

#### SQL Execution

The SQL execution task allows you to run SQL statements against a database connect.

#### Talend Job Execution

The Talend Execution task allows you to run a compiled job that was built in Talend Open Studio.  Using Talend, you can create complex ETL logic that can be executed within foreflow.  Read more about handling Talend errors [here](/docs/{{version}}/talend_tasks).

## Batches & Packages

Batches and Packages are used to organize tasks into logical groups.  Tasks can be organized into Batches, where they can be executed in parallel or in sequence.  Likewise, Batches can be organized into Packages, where they can be executed in parallel or in sequence.

## Scheduling

Tasks, Batches, and Packages can be scheduled to run at certain frequencies.  When viewing a Task, Batch, or Package, there is a "Schedule" button that will present a dialogue which you can use to schedule the item being viewed.

There are many options available when choosing the frequency of the schedule. 

