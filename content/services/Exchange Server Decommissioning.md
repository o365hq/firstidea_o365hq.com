+++
title = "Exchange Server Decommissioning"
description = "Microsoft Exchange Server safe decommissioning in your organization."
date = 2019-06-26

[taxonomies]
products = ["Windows Server SCCM"]
types = ["Implementation"]

[extra]
sku = "ITPWW360IMPOT"
price = "$1380"
duration = "3 days"
manager = "Roman Sotnik"
+++

This procedure may be required if you have refused to use On-Premises
Microsoft Exchange in favor of Exchange Online and you need to remove
all Exchange traces from your domain. Incorrect removal of Exchange can
lead to problems in the further domain operation and make it impossible
to reinstall Exchange, integrate AD with various services.

### IT Partner responsibilities:

1.  Gathering information
2.  Data backup
3.  Correct decommissioning of Microsoft Exchange

### Client responsibilities:

1.  Coordinate Client resources and staff schedules
2.  Provide a dedicated point of contact responsible for working with IT
    Partner
3.  Review and approve engagement deliverables in a timely manner
4.  Request and approve all change management tickets (if available)
    in the Client environment
5.  Provide access to physical and virtual servers as needed
6.  Coordinate any outside vendor resources and schedules
7.  Configure all networking equipment such as load balancers, routers,
    firewalls, and switches

### Prerequisites:

1.  Microsoft Exchange is correctly installed in your organization
2.  Microsoft Exchange is not used for sending or receiving mail, as
    well as for any other purposes

### Plan:

The plan may vary depending on your needs.

1.  Kickoff meeting
2.  Preparing a domain for Exchange uninstalling
3.  Data backup
4.  Exchange uninstalling
5.  Verification and fixing issues

### Success Criteria:

1.  Exchange server removed from your organization
2.  No Exchange attributes and data in Active Directory
3.  User work not disrupted