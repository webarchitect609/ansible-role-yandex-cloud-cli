Ansible Role: Yandex Cloud cli
==============================

[![Build Status](https://github.com/webarchitect609/ansible-role-yandex_cloud_cli/actions/workflows/build.yml/badge.svg)](https://github.com/webarchitect609/ansible-role-yandex_cloud_cli/actions/workflows/build.yml)
[![Latest version](https://img.shields.io/github/v/tag/webarchitect609/ansible-role-yandex_cloud_cli?sort=semver)](https://github.com/webarchitect609/ansible-role-yandex_cloud_cli/releases)

[![Downloads](https://img.shields.io/ansible/role/d/webarchitect609/yandex_cloud_cli)](https://galaxy.ansible.com/ui/standalone/roles/webarchitect609/yandex_cloud_cli)
[![License](https://img.shields.io/github/license/webarchitect609/ansible-role-yandex_cloud_cli)](LICENSE.md)
[![More stuff from me](https://img.shields.io/badge/galaxy-webarchitect609-000)](https://galaxy.ansible.com/ui/standalone/namespaces/7493/)

Installs [Yandex Cloud cli](https://yandex.cloud/en-ru/docs/cli/) tool from the official source.

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
     - { role: webarchitect609.yandex_cloud_cli }
```

License & Author Information
----------------------------

[BSD-3-Clause](LICENSE.md)
