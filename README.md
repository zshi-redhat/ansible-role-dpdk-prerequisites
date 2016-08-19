Ansible Role: dpdk-prerequisites
=========

Set up dpdk prerequisites on RHEL.

Requirements
------------

Supports intel iommu and 1G hugepages on test Server.

Role Variables
--------------

hugepages_size: ""
hugepages_count: ""

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: remote_servers
      roles:
         - { role: ansible-role-dpdk-prerequisites }

License
-------

BSD

Author Information
------------------

This role was created in Aug 2016 by Zenghui Shi
