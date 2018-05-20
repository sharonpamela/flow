.. Adding labels to the beginning of your lab is helpful for linking to the lab from other pages
.. _example_lab_1:

-------------
Enable Flow
-------------

Overview
++++++++

Flow can only be enabled once per cluster. Since the cluster you are working on may be a shared environment, decide on which member of the team will complete the task.

Enable Flow
++++++++++++++++++++++

Open https://<PRISM-CENTRAL-IP>:9440 in your browser to access Prism. Log in as a user with administrative privileges.
-----------------------------------------------------

Open \https://<*NUTANIX-CLUSTER-IP*>:9440 in your browser to access Prism. Log in as a user with administrative priveleges.

.. figure:: images/PC-logon.png

Click the question mark at the top right corner of the Prism UI > **Microsegmentation**.

.. figure:: images/enableMicrosegmentation.png

Note

If **Enable Microsegmentation** is already green, that means Microsegmentation has been enabled already. Move on to the next part if this is the case.

  - **Name** - VM VLAN
  - **VLAN ID** - *Refer to your Environment Details Worksheet*
  - **Network IP Address/Prefix Length** - *Refer to your Environment Details Worksheet*
  - **Gateway IP Address** - *Refer to your Environment Details Worksheet*
  - **Domain Name Servers** - *Refer to your Environment Details Worksheet*

.. figure:: images/3.png

Click **Submit > Save**.

Takeaways
+++++++++

- Here is where we summarize any key takeaways from the module
- Such as how a Nutanix feature used in the lab delivers value
- Or highlighting a differentiator
