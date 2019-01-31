ansible-role-ipa-client
=======================

Install ipa-client software packages to allow for central auth/ID management
using [Red Hat IdM](https://access.redhat.com/products/identity-management).

Requirements
------------

[Red Hat IdM](https://access.redhat.com/products/identity-management) server.

Role Variables
--------------

There is list of variables in defaults/main.yml which can be overridden in
vault or in Tower. You may need to modify them to use this role.

Dependencies
------------

No dependecies.

Example Playbook
----------------

- include_role:
    name: ansible-role-ipa-client


License
-------

BSD

Author Information
------------------

Peter Gustafsson, pgustafs@redhat.com
[Red Hat](https://redhatnordicssa.github.io/)
