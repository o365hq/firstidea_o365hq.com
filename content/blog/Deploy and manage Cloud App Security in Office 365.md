+++
title = "Deploy and manage Cloud App Security in Office 365"
description = "Before we jump into the cloud app security implementation or the management processes, let&#8217;s talk about the cloud app security what it is and why would do we need cloud app security. It’s a Microsoft cloud-based solution that gives you insights into your suspicious user activities. "
date = 2019-06-04

[taxonomies]
tags = ["cloud security", "microsoft 365", "office 365", "tenant security"]
+++

![](https://o365hq.com/images/357.png)

You can generate an email with others and you can configure some
remediations against security alerts based on the user's activities.
Cloud app security is a requirement if you have looking at Implementing
Office 365 a cloud-based application to protect your data and get
insights into your security solutions because you need solutions like
firewall or IPS. They do not have the capability for you to
give you insights on what users are doing in the cloud and how they are
accessing or sharing the data with external parties.

![](https://o365hq.com/images/351.png)

Cloud App Security is a complete framework that gives you insights on
the user's activities. You can get the insights on the user's activities
by having the discovery of your network. You can do the discovery by
uploading your end users or firewall logs or the user activity logs to
your server. You can do this at a onetime upload to get a snapshot
report where you can see your sanctioned or un-sanctioned applications
being used by the users.

Then you have information protection based on the which you can use the
DLP policies in Office 365 or Azure information protection
policies to apply the production on your data into Office 365. That does
include like you can have the ability to encrypt the data in the cloud
or you can actually block the access based on the DLP policies.

The third one is a Threat Prevention where you actually define the
behavior-based activities and the alerts against those like if users are
trying to download the data from an unmanaged device, what actions
should be taken to stop users from downloading the data. You can suspend
user's accounts or you can ask users to sign back into the application
or go with the security procedures that we have in the company.

And the last one is in-session control. Within the application, this is
a new feature that was being announced like 6 or 8 months ago. In-
session control, where you actually have the users to go through
particular activities if they are trying to do something within these
applications like

if I'm trying to share my data through OneDrive for business with the
external parties you can go in for the inspection controls to have the
company policies on top of that to restrict me from sharing my data with
third parties.

![](https://o365hq.com/images/352.png)

Cloud App Security architecture and how it works at this at the very
first step in the cloud app security is you actually have a discovery
component where you can actually have your discovery of your network to
see the sanctioned and unsanctioned applications. You can get this
particular report by uploading your firewall logs and the onetime report
to get this snapshot or the second step is you can actually have
automatic log configurations that can upload the logs to cloud app
security.

We highly recommend that you use automatic firewall logs uploaded to the
Office 365 cloud app security so that you can have a continuous report
on your end user's activities in the insights within your on-premises
network as well.

Once you have the insights on the second step is the sanctioned and
unsanctioned applications and that's one of the one recent surveys more
than 80% of the employees have admitted that they are using
un-sanctioned applications within the infrastructure to do their
day-to-day jobs.\
Which means you have like 80% risky users within that company as well
that are doing un-sanctioned applications and doing their day-to-day job
which can have a data breach concerns for you guys and other security
company.

Next one is the App connector. Within the cloud App security the App
connector is using APIs on the back end to have your third
different third-party application integrations to give you the insights
like from sales force or if you are using a CRM or third-party
SaaS applications, you can have the APIs integration with them
to get the insights of the users activities within the third-party
applications as well.

Next one is the Conditional Access and this is based on the Azure Active
Directory as well where you actually can have the conditional access
policies in force on the end users for the cloud app security based on
their activities. You can have the users to assign them back in or you
can have user access being blocked based on their activities. And
another control within the cloud app security is the Policy-Based
control where you can have the controls on the end users, when they are
trying to access the applications from a certain application of the
unmanaged platform, where you can enforce the users policy based action
controls on what the user can do from an unmanaged device versus the
managed device in the organization and this is all being driven through
the cloud app security policies.

![](https://o365hq.com/images/350.png)

In order for you to deploy the cloud app security, there are 4 basic
steps. Number one is you need to create a trial tenant or you can have a
Cloud App Security as part of your E5 license or you can sign up for a
trial tenant and as well.

Once we have a trial tenant setup you can actually upload your network
firewall logs or you can have a manual logs uploader as well. Again, we
highly recommend that you upload configured automatic uploads of the
logs. This can be done directly through the firewalls or you can have a
server on-premises that can collect the logs from all of your devices
and then upload those logs to the Office 365 cloud app security. Next
one is once you have the logs uploaded you actually need to connect your
sanctioned applications and blocked the access of the other
un-sanctioned applications.

Microsoft team of analysts they have about 30,000 plus application that
is ranked based on their regularity requirements and the security
controls in the risk or on top of that.

The last one is the configuration of the policies. By default, when you
enable cloud app security.

It gives you 10 built-in policies as well as far as your configuration
which gives you like an awful behavior of the users, user sign in from
risky locations or unexpected travel for the user and all these things.

![](https://o365hq.com/images/353.png)

Within the discovery phase of the cloud, cloud app security, it gives
you the Shadow ID discovery, it gives a cloud application risk
assessments and Alert on risky cloud usage.

Shadow IT discovery is the usage of the unapproved ID applications that
are being used by the end users.

Another said there are more than 80% of the employees in each
organization that is using unapproved ID applications to perform their
day-to-day operational tasks and wish open apps your organization to the
risk of the exposure to the third-party companies.

And then the cloud application risk assessment is based on the ID
security controls and the regulatory requirements of the companies and
then it does have some policies from the Microsoft team of analysts as
well that access each and every application against more than 60 plus
controls from Microsoft to ensure whether this application risky or this
application is safe to use within the organization. You can customize
those particular controls based on your requirements on your security
posture and it will give you the ranking and rating of the application
whether this application can be used within the organization or not. Or
if it's risky whether you want to allow this application to be used in
your organization.\
The last one is Alerts on risky activities. You can actually have the
alerts configured in the Azure cloud app security, where your users are
performing the risky activities like having an unexpected travel to
somewhere which is not possible therefore within 5 minutes of such
travel from one location to the other location it actually generates the
alerts on my activities or downloading from Sharepoint or OneDrive from
one of the IPs where from where he never logged into Office 365 as well.

![](https://o365hq.com/images/355.png)

The next one is Information protection. So once we have the discovery
and we have the insights on if we have some malicious activities or
rather trying to download the data or having some alerts you can apply
some automatic policies as well to protect the data or the users
behaviors, where you can use the office DLP policies or Azure
information protection policy is where you can restrict to download the
data from unprotected device or from the risky network which means
outside of my company network or you can apply the Azure information
protection to encrypt the data in cloud as well as the data which is
being downloaded on my machine as well.

![](https://o365hq.com/images/356.png)

The third one is Threat detection. So once I have the policies in force
I have information protection policies applied. The next step is
enforcing that we are actually remediating against those threads. So in
cloud app security, you can actually have automatic remediation as well
where you can configure the policies and the actions against that. And
those actions can be applied based on your configurations where you can
indicate if we someone is trying to access the data from a risky
location you can suspend that user.

![](https://o365hq.com/images/354.png)

In-Session control. This is new. This one is being released 8 months
ago. In-session control you can actually define the user's behavior and
you can define if the user accessing a certain application.

What you need to do when the user is performing some malicious
activities within the application. Do you want to block my access or
revoke my access to that application, this can be achieved with the
integration with Azure Active Directory.

And the next one is how you can try the cloud app security. You can go
to the Microsoft website on the cloud app security portal and you can
sign up for the trial and you can play around with the cloud app
security and then you can modify those one. Or you can actually have the
cloud app security available as part of the Office 365 E5 license or the
EMS licenses.