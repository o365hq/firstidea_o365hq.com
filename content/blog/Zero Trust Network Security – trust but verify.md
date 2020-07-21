+++
title = "Zero Trust Network Security – trust but verify!"
description = "Perimeter-based networks protected by a firewall are familiar to anyone because they were so common. But the key word is “were”, because they are outdated now. They function assuming that machines and users within a perimeter are reliable – but it actually never was the case and least of all it applies to modern reality when Bring your own device (BOYD) and Bring your own cloud (BYOC) trends are in place, and cybercriminals are getting more sophisticated than ever before. The previous generation of networks cannot accommodate modern workstyles and cannot perform their main role of protecting data, as when the cyber-criminals compromise even one end-point within a perimeter, they can laterally move there to extract sensitive business data. "
date = 2019-04-29

[taxonomies]
tags = ["advanced threat protection", "cloud security", "microsoft 365", "microsoft azure, office 365"]
+++

The limitations of this model were improved in an alternative IT
security architecture called Zero-trust. It relies on the idea that all
your resources are accessible by the open Internet and to avoid breach
you should verify everything using both device and user claims. The
control plane of this model is the user's identity.

![](https://o365hq.com/images/321.png)

This model protects the data in three ways:

1.  at the point the *access to the data* there is a bunch of things you
    can learn, like who the users are, what roles they are in, what
    their normal behavior patterns are, what their expected application
    usage is, based on who they are in the company etc.
2.  on the device (when it is verified if it is pin-locked, encrypted,
    secure and compliant);
3.  secure in transit as the data flows.

Every sector contains specific recommendations that can enhance your
security:

![](https://o365hq.com/images/322.png)

One sector that is missing is intelligence and it deserves special
attention. Microsoft's team alone on the identity protection side, is
evaluating 18 billion log-ins a day processing something like 40
terabytes of data through the machine learning systems a day. It's a
volume of data that's hard to replicate and the intelligence brings a
prominent advantage. The intelligent security graph, bringing those
things together, helps you understand where the threats are and what you
should and shouldn't allow.

![](https://o365hq.com/images/325.png)

This information is pulled together to provide the continuous
verification process, called conditional access. It is built around the
idea of moving to a world of mobility, mobile devices, networks that may
be everywhere, say, in conference centers, and apps that are hosted in
the cloud on infrastructure you didn't buy or deploy and that you didn't
write the code for. Conditional access is a secure starting point to get
control in this environment, and it comprises conditions and controls,
where conditions play the role of policy selector.

![](https://o365hq.com/images/326.png)

From this mind-blowing picture, you can see that thanks to conditional
access every user is checked because nobody can be trusted. During every
log-in your fine-tuned security system can detect a bunch of
observables, like the kind of user; is he/she coming in from a
particular network or not; is he/she coming in on a particular type of
device, or app, what's the user's physical location and etc.

The second piece of information to intersect is the history of the
users' log in, like what have they done before, if that IP is an IP they
have been on before, is that device a device they have been on before;
is this a time of day they normally go to the service. All that
information filters in becoming part of the session risk.

The third thing requested to filter in is the environment, telling
things like is this device currently on a botnet, is this IP address one
that's currently involved in an active attack against the system etc.

Evaluating the user's log in activity, the history of the user and the
environment, zero trust network will choose what policy to apply
depending on what things have happened, meaning what conditions it
observed.

The other part of the model is built around the concept of control. You
can imagine control as a place, where a client is sent to get a claim
for more information so the log in activity could be finished. For
example, you attempt to log in, the system looks at the way that you are
logging in, it looks at the claims you are carrying and decides if it
needs more information, and if it does, you are sent away for more.

So, on the one hand -- conditions, on the other hand -- claims give you
a ton of power. In addition to just granting or denying access, the
system can do something fairly cool, which is to decorate the ticket it
is issuing with instructions to the relying party. The best example of
this is with SharePoint. The system can send them an instruction that
states -- given the nuances of the session, the download is restricted
by the admin. This is an "upgrade" of conditional access when the system
not only expresses whether you should be issued a ticket, but what are
the conditions of the issuance of that ticket.

![](https://o365hq.com/images/324.png)

This extended kind of conditional access is expanding on an ongoing
basis, though so far it is only present with SharePoint and Outlook web
access. These restrictions prevent data from flowing onto a device that
you haven't managed or in a situation you don't like -- this is the hub
of the control surface.

### The components of the new security architecture?

-   *Identity provider (like AAD)* to keep an eye on users and
    their details.
-   *Device directory* to monitor if the machines are managed and
    healthy.
-   *Policy evaluation service* to check if you comply with the rules
    introduced by admin every time you log in with your identity and
    your device.
-   *Access proxy*, which decides if the user can be admitted to a
    resource or not considering the signals from the services, we have
    mentioned.
-   *Anomaly detection* to recognize anomalies at scale and act
    respectively to the controls implemented.

### How do you start with zero-trust architecture?

To move one step closer to this new network architecture, you'd better
start with asking questions about your environment. The thorough
estimation will help you understand:

1.  persona of the users (whether they are executives, first-line,
    help-desk or retail workers),
2.  apps, they are accessing (like mail or some LOB apps)
3.  the way they are doing it (through VPN, other zero-trust
    solution, is it obligatory to be on-premises to get access).

Surely, you will need time to figure out all the answers, but only this
information will help you lay down conditions to access a corporate
resource. Based on these conditions you can then apply controls, which
look like an if-then statement. For example, if you come from an
unmanaged device, should you be prompted to enroll your device in
MDM or challenged with MFA; if your identity is for
sale in the public Internet, should you be forced to password reset or
just denied access? Creating a policy, you answer all these questions
and define the controls for every condition.

### Conclusion

The old model of perimeter-based network was very restricted, but it
still wasn't very safe. One thing it allowed you to do was to deceive
yourself, that everything was cool, because once you are on the network
it's fine. This model also limited the flexibility of employees, as they
were stuck in one location. In this light the benefits of zero-trust
model are literally obvious -- you not only secure your resources and
prevent compromised identities and non-managed devices from entering
your network, but you can reach the heights of productivity as the users
are able to work however they want, where they want and when they want.
