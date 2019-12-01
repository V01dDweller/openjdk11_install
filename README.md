openjdk\_install
================

Installs OpenJDK 11 on EL 7 Linux.

Requirements
------------

* ssh access to the inventory
* sudo to root

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

```yaml
---
- name: Install OpenJDK 11
  hosts: all
  become: yes
  roles:
    - V01dDweller.openjdk11_install
```

License
-------

BSD

Author Information
------------------

Written by V01dDweller in 2019.
