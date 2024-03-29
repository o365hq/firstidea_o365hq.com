+++
title = "SQL Server DB migration to SQL Server in Azure VM (with server upgrade)"
description = "We will copy databases from your own sql server to the newest version of sql server in an Azure VM. "
date = 2018-06-27

[taxonomies]
products = ["Microsoft Azure"]
types = ["Migration"]

[extra]
sku = "ITPWW280MIGOT"
price = "$150 per hour"
duration = "1 week"
manager = "Mike Mackey"
+++

We can migrate in the Cloud and upgrade your instances of SQL
Server 2008, SQL Server 2008 R2, SQL Server 2012, or
SQL Server 2014 to SQL Server 2016.

Please note that this service requires some downtime. We will try to
minimize it.

Our **objective** is to migrate SQL databases to Azure VM and
upgrade your SQL Server to the newest version. This project
will be considered **successful** when SQL databases are
available from Azure without data loss.

### IT Partner responsibilities

-   Back up all SQL Server database files from the instance to
    be upgraded, so that you can restore them, if required.
-   Run the appropriate Database Console Commands (DBCC) on
    databases to be upgraded to ensure that they are in a consistent
    state.
-   Disable all startup stored procedures, as the upgrade process will
    stop and start services on the SQL Server instance being
    upgraded.

Stored procedures processed at startup time might interfere with the
upgrade process.

-   Perform a full database backup to an on-premises location.
-   Create a virtual machine with the desired version of SQL
    Server.
-   Setup connectivity.
-   Connect to SQL Server over the Internet or in the same
    virtual network.
-   Copy file(s) to VM.
-   Configure your new SQL Server installation.

### Out of the scope of this project (additional cost items)

Upon completion of the project, we will provide a *project closeout
report*. This document will indicate the final project status including
evidence of meeting acceptance criteria, outstanding issues and the
final budget. If you require more extensive documentation, this can be
provided for an additional fee.

### Plan

May vary depending on your needs.

1.  Kickoff meeting
2.  Review SQL server and Windows Server
3.  Start deployment
4.  Finalize deployment
5.  Verify and fix issues