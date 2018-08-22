AnsibleRoleRaspberryPiExpandFileSystem
=========

This role will expand root filesystem to size of underlying SD card.

Requirements
------------

None

Role Variables
--------------

None

Dependencies
------------

This role don't depends on any other Anisble role.

Example Playbook
----------------

Below there's example playbook which can be used:

    - hosts: servers
      roles:
         - { role: kamikazestar.AnsibleRoleRaspberryPiExpandFileSystem }

License
-------

MIT

Author Information
------------------

[Marcin Slabonski](https://github.com/kamikazestar)
