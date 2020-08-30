# Orchestration Tasks &mdash; QuickBooks Online Import

-   [Introduction](#introduction)
-   [QuickBooks Online Import](#quickbooks-online-import)

<a name="introduction"></a>

## Introduction

QuickBooks Online Import tasks handle the importing of Customer and Invoice data into QuickBooks Online.

<a name="quickbooks-online-import"></a>

## QuickBooks Online Import

The QuickBooks Online Import task is used import Customer and Invoice data into QuickBooks Online.

-   **Connection** &mdash; The QuickBooks Online connection you would like to use for the import process
-   **Source Table** &mdash; The Table that contains the Customer and Invoice data that will be imported into QuickBooks Online

When a Connection and Source table are selected, you will be prompted to map fields from your source table into the corresponding fields in QuickBooks Online.  Your source table should contain the columns necessary to map to the following fields in QuickBooks Online:

<div markdown="1" class="table-wrap">

| Destination Column | Required | Description |
| ------------------------ | -------- | ------------------------------------------------------------------------------------ |
| `BILLING LINE 1`         | YES      | Line 1 of the customer's billing address                                             |
| `BILLING LINE 2`         | YES      | Line 2 of the customer's billing address                                             |
| `BILLING CITY`           | YES      | City of the customer's billing address                                               |
| `BILLING STATE`          | YES      | Two letter state abbreviation of the customer's billing address                      |
| `BILLING POSTAL CODE`    | YES      | Postal Code of the customer's billing address                                        |
| `CUSTOMER ID`            | NO       | QuickBook's Customer ID to which the Invoice belongs                                 | 
| `CUSTOMER NAME`          | YES      | The name of the Customer to which the Invoice belongs                                |
| `TRANSACTION DATE`       | YES      | The transaction date of the Invoice                                                  |
| `DUE DATE`               | YES      | The DUE date of the Invoice                                                          |
| `DOCUMENT NUMBER`        | YES      | The document number that should be used to identify the Invoice in QuickBooks Online |
| `ITEM ID`                | YES      | QuickBook's Item ID which represents the Product or Service being sold               |
| `ITEM DESCRIPTION`       | YES      | The name of the Product or Service being sold                                        |
| `LINE AMOUNT`            | YES      | The dollar amount of the line on the invoice                                         |
| `LINE DESCRIPTION`       | NO       | A description of the line on the invoice                                             |

</div>

In addition to the fields above, you can provide up to three Custom Fields to include in the import.  These Custom Fields should exist on your Invoice in QuickBooks Online already.

When a QuickBooks Online import takes place, the system will create any Customer records in the Source table that don't already exist in your QuickBooks Online - Customers table.  It will then associate invoices with that new Customer Record in QuickBooks Online.  It is important to have up-to-date information in your other QuickBooks Online tables prior to running an import.  

When an import completes, foreflow will automatically truncate the source table, to prevent any Invoice duplication in QuickBooks Online.