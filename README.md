ansible-role-frp
================

Install and optionally configure [frp](https://github.com/fatedier/frp) client and/or server.

    ansible-galaxy install bit_kitchen.frp

Requirements
------------

None.

Role Variables
--------------

See [defaults](defaults) and [vars](vars).

Dependencies
------------

* `bit_kitchen.nssm`: used for service creation.

Example Playbook
----------------

    - hosts: servers
      roles:
        - bit_kitchen.frp

License
-------

[MIT](LICENSE)

Author Information
------------------

[bit.kitchen](https://github.com/bit-kitchen)
