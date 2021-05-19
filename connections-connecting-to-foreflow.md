# Connecting To foreflow

-   [Introduction](#introduction)
-   [Prerequisites](#prerequisites)
-   [Application Instructions](#application-instructions)
    - [Table Plus](#table-plus)
    - [Sequel Pro](#sequel-pro)

<a name="introduction"></a>

## Introduction

Some advanced users may wish to connect directly to the foreflow database using different applications. Currently the only supported method is connecting using SSH.

Below you will find instructions for connecting to foreflow using different clients.

<a name="prerequisites"></a>

## Prerequisites

To connect directly to the foreflow database you'll need to obtain the following from your Administrator or foreflow Account Manager:

1. Server IP Address or domain (e.g. `yourcompany.foreflow.com`)
2. SSH username
3. SSH password (or SSH key)
4. Database name (typically `foreflow`)
5. Database username
6. Database password

<a name="application-instructions"></a>

## Application Instructions

<a name="table-plus"></a>

### TablePlus

[TablePlus](https://tableplus.com/) is a Database management tool available for MacOS and Windows.

1. Create a new connection
2. Choose "MySQL" for the type
3. Enter a desired name for the connection in the "Name" field
4. Click the "Over SSH" button at the bottom of the "MySQL Connection" window
5. Enter the IP Address or domain name
6. Enter the SSH username in the lower "User" field
7. Enter the SSH Password (or select the SSH Key) in the lower "Password" field
8. Enter the Database name in the "Database" field
9. Enter the Database username in the upper "User" field
10. Enter the Database password in the upper "Password" field
11. Click "Test" to verify the connection and "Save" to store the connection in TablePlus

![table-plus-new-connection](/{{version}}/img/connecting-to-foreflow-tableplus.jpg)

<a name="sequel-pro"></a>

### Sequel Pro

[Sequel Pro](https://sequelpro.com/) is a Database management tool available for MacOS.

1. Create a new connection
2. Click the "SSH" button at the top instead of "Standard"
3. Enter a desired name for the connection in the "Name" field
5. Enter the IP Address or domain name in the "SSH Host" field
6. Enter the SSH username in the "SSH User" field
7. Enter the SSH Password (or select the SSH Key) in the "SSH Password" field
8. Enter the Database name in the "Database" field
9. Enter the Database username in the "Username" field
10. Enter the Database password in the "Password" field
11. Click "Test Connection" to verify the connection and "Add to Favorites" to store the connection in Sequel Pro

![sequel-pro-new-connection](/{{version}}/img/connecting-to-foreflow-sequelpro.jpg)