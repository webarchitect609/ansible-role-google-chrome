Ansible Role: Google Chrome
===========================

[![Build Status](https://github.com/webarchitect609/ansible-role-google-chrome/actions/workflows/build.yml/badge.svg)](https://github.com/webarchitect609/ansible-role-google-chrome/actions/workflows/build.yml)
[![Latest version](https://img.shields.io/github/v/tag/webarchitect609/ansible-role-google-chrome?sort=semver)](https://github.com/webarchitect609/ansible-role-google-chrome/releases)
[![Downloads](https://img.shields.io/ansible/role/d/30616)](https://galaxy.ansible.com/ui/standalone/roles/webarchitect609/google_chrome/)
[![License](https://img.shields.io/github/license/webarchitect609/ansible-role-google-chrome)](LICENSE.md)
[![More stuff from me](https://img.shields.io/badge/galaxy-webarchitect609-000)](https://galaxy.ansible.com/ui/standalone/namespaces/7493/)

Installs [Google Chrome](https://www.google.ru/intl/en/chrome/) from the official repository.

Requirements
------------

None.

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

None.

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
    - { role: webarchitect609.google_chrome }
```

License & Author Information
----------------------------

[BSD-3-Clause](LICENSE.md)
