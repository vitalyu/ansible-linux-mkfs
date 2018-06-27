linux-mkfs
=========

Creates filesystem and mount it. Support list of filesystems

Requirements
------------

Linux distribution. lsblk, mkfs utils

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
        - linux-mkfs
      vars:
        mkfs:
          - filesystem_type: 'xfs'
            device: '/dev/sdb1'
            mount_point: "/home"
            mount_options: "nobarrier,noatime"

License
-------

MIT

Author Information
------------------

Vitaly Uvarov https://vitalyu.ru
