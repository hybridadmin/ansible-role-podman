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

The variables below can be edited in [`defaults/main.yml`](defaults/main.yml) to customize the deployment:

    podman_compose_install: true

This installs `podman-compose` when set to `true`

    podman_buildah_install: true

`buildah` is installed together with `podman` when set to `true`.


Dependencies
------------

None.


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
    - hosts: servers
      vars:
        podman_compose_install: true
        podman_buildah_install: true
      roles:
         - { role: hybridadmin.podman }
```


License
-------

[`Apache License 2.0`](./LICENSE)

Author Information
------------------

Created by [`hybridadmin`](https://github.com/hybridadmin).
