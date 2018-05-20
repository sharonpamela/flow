-------------
Glossary
-------------

Application Security Policy
+++++++++++++++++++++++++++

Use an application security policy when you want to secure an application by specifying allowed traffic sources and destinations.

Isolation Environment Policy
++++++++++++++++++++++++++++

Use an isolation environment policy when you want to block all traffic, regardless of direction, between two groups of VMs identified by their category. VMs within a group can communicate with each other.

Quarantine Policy
+++++++++++++++++

Use a quarantine policy when you want to isolate a compromised or infected VM and optionally want to subject it to forensics. You cannot modify this policy. The two modes to quarantine a VM are Strict or Forensic.

Strict: Use this value when you want to block all inbound and outbound traffic.

Forensic: Use this value when you want to block all inbound and outbound traffic except the traffic to and from categories that contain forensic tools.

AppTier
+++++++

Add values for the tiers in your application (such as web, application_logic, and database) to this category and use the values to divide the application into tiers when configuring a security policy.

AppType
+++++++

Associate the VMs in your application with the appropriate built-in application type such as Exchange and Apache_Spark. You can also update the category to add values for applications not listed in this category.

Environment
+++++++++++
Add values for environments that you want to isolate from each other and then associate VMs with the values.
