podman
=========

> Ansible role to install podman on all supported distros.

Requirements
------------

* ansible version >= 2.9
* Ansible Collections:
  * [`community.general`](https://github.com/ansible-collections/community.general)


Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

The variables below can be edited in [`defaults/main.yml`](defaults/main.yml) to customize the deployment:


Dependencies
------------

None.


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
    - hosts: servers
      roles:
         - { role: hybridadmin.podman }
```


License
-------

[`Apache License 2.0`](./LICENSE)

Author Information
------------------

Created by [`hybridadmin`](https://github.com/hybridadmin).
