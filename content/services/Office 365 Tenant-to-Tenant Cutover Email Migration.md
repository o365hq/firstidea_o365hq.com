+++
title = "Office 365 Tenant-to-Tenant Cutover Email Migration"
description = "Mailbox migration from one Office 365 tenant to another. Usually, you will need this type of migration when a company merges or acquires another company, or you would like to migrate to a different geographic region."
date = 2019-09-11

[taxonomies]
products = ["Office 365"]
types = ["Migration"]

[extra]
sku = "ITPWW460MIGOT"
price = "$700 + $27 per mailbox"
duration = "1 week"
manager = "Roman Sotnik"
+++

Occasionally, a customer needs a migration inside the Office 365 cloud
platform. For example, if one company acquires another company and both
are using Office 365, there may be many reasons to start merging. 

Our objective is to provide planning, design, and migration of email
service from one Office 365 tenant to another. 

There will be some email downtime with this migration due to the time
required to remove the domain on the Source tenant and add it on the
Destination tenant. This is because Microsoft only allows the same
domain to exist on one Office 365 tenant at a time. ​​Exchange Online
Protection (EOP) can't route email for the domain during the
period of time when the domain is removed from the Source tenant and
added to the Destination tenant, assuming the MX record is pointed at
EOP. This results in senders getting a non-delivery report
(NDR). Read the Move domains and settings from one EOP
organization to another EOP organization TechNet article for
options to queue email during this time

If short-term downtime and the possibility of losing some emails are not
acceptable for you, please see another service [Office 365
Tenant-to-Tenant Cutover Email Migration Without Downtime and Bounced
Email](https://o365hq.com/services/office-365-tenant-to-tenant-cutover-emai-migration-without-downtime-and-bounced-email)
.

### IT Partner responsibilities

1.  Export resources (mailbox-enabled users, contacts, groups, etc.)
    from the source tenant
2.  Import resources to the destination tenant via AD Connect
    or CSV import
3.  Do pre-stage migration (only emails and email folders older than 30
    days)
4.  Final mailbox migration with calendars, contacts, rules and other
    data
5.  Change records in domain zones to accommodate migration needs

### Client responsibilities

1.  Provide a dedicated point of contact responsible for working with IT
    Partner
2.  Coordinate any outside vendor resources and schedules
3.  Configure all network equipment such as load balancers, routers,
    firewalls, and switches
4.  If Microsoft Outlook or other desktop email clients are used to
    connect to Office 365, deploy email software on client workstations
5.  Perform changes to internal and external DNS, as required
6.  Assist with identification of high-risk users (top executives
    and VIP-users, users with 50 GB mailboxes or larger and/or
    30 GB deleted folders or larger)
7.  Recreate new Outlook profile on all client workstations, if desktop
    Outlook version is used
8.  Inform users about upcoming changes and provide the necessary
    information

### Additional cost items not provided by the project

1.  Informing users about upcoming changes
2.  Сustomer team training (could be added as additional service)
3.  Migration of Corporate documents to SharePoint Online (could be
    added as additional service)
4.  Desktop software settings

Upon completion of the project, we will provide a project closeout
report. This document will indicate the final project status including
evidence of matching acceptance criteria, outstanding issues and the
final budget. If you require more extensive documentation, it can be
provided for an additional fee.  

### Prerequisites

1.  You must have global-admin level access to the source Office 365
    tenant
2.  You must have global-admin level access to the destination Office
    365 tenant with Exchange Online licenses available
3.  You must have access to your email domain DNS zone

### Plan

The plan may vary depending on your needs.

1.  Kickoff meeting
2.  Pre-migration source system health check
3.  Creating users or configuring AD Connect tool
4.  Email migration start
5.  Verification of email migration
6.  Changing MX record to new Office 365 tenant
7.  Final email migration
8.  Post-migration tasks

### Success criteria

1.  Users can access Exchange Online on their desktop PCs, mobile phones
    and tablets from any place, any time
2.  Old Office 365 tenant successfully migrated to new Office 365 tenant
    and accessible by all users
3.  All necessary Transport rules created and working
4.  Mail can be sent and received using Exchange Online
5.  Exchange Online Protection is configured and working