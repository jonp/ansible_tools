Role Name
=========

A brief description of the role goes here.

Requirements
------------

- ssh-keyscan

Role Variables
--------------

- Required: hosts, a list of host names that will be added to known_hosts

Dependencies
------------

none

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```
- hosts: localhost
  gather_facts: no
  vars:
    - import_role:
        name: known_hosts
        tasks_from: add
      vars:
        hosts:
          - this.is.a.host.example.com
          - 192.168.0.1
          - myhost
```

License
-------

CC-BY-4.0

Author Information
------------------

jonp
