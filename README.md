Ansible Role: crb
=========
[![CI](https://github.com/egdoc/ansible-role-crb/actions/workflows/ci.yml/badge.svg)](https://github.com/egdoc/ansible-role-crb/actions/workflows/ci.yml)
[![Release](https://github.com/egdoc/ansible-role-crb/actions/workflows/release.yml/badge.svg)](https://github.com/egdoc/ansible-role-crb/actions/workflows/release.yml)


Ansible role to manage CRB repository on RHEL and clones

Requirements
------------

This role requires the community.general collection to be installed

Role Variables
--------------

```yaml
crb_repo_enabled: true
```
Whether the crb repository should be enabled.

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: egdoc.crb

License
-------

GPLv2

Author Information
------------------

Created by Egidio Docile.
