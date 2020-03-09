ansible-role-frp
================

Install and configure [frp](https://github.com/fatedier/frp) client or server.

    ansible-galaxy install bit_kitchen.frpc
    ansible-galaxy install bit_kitchen.frps

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

    - hosts: clients
      roles:
        - bit_kitchen.frpc

    - hosts: servers
      roles:
        - bit_kitchen.frps

License
-------

[MIT](LICENSE)

Author Information
------------------

[bit.kitchen](https://github.com/bit-kitchen)
