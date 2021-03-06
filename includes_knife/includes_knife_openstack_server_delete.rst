.. The contents of this file are included in multiple topics.
.. This file describes a command or a sub-command for Knife.
.. This file should not be changed in a way that hinders its ability to appear in multiple documentation sets.


The ``server delete`` argument is used to delete one or more instances that are running in the |openstack| cloud. To find a specific cloud instance, use the ``knife openstack server list`` argument. Use the ``knife node delete`` and ``knife client delete`` sub-commands to delete associated node and client objects (if required).

This argument has the following syntax::

   knife openstack server delete [SERVER...]

This argument has the following options:

``-A ID``, ``--openstack-access-key-id ID``
   |openstack-access-key-id|

``-K SECRET``, ``--openstack-secret-access-key SECRET``
   |openstack-secret-access-key|

``--openstack-api-endpoint ENDPOINT``
   |openstack-api-endpoint|

``--region REGION``
   |region openstack|

**Examples**

For example, to delete a server named "qa-test-01", enter:

.. code-block:: bash

   $ knife openstack server delete qa-test-01

