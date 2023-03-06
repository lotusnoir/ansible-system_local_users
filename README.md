# ansible-system_local_users

## Description

[![Galaxy Role](https://img.shields.io/badge/galaxy-system_local_users-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/system_local_users)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-system_local_users.svg)](https://github.com/lotusnoir/ansible-system_local_users/releases/latest)
[![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-system_local_users?color=orange&style=flat)](https://galaxy.ansible.com/lotusnoir/system_local_users)
[![downloads](https://img.shields.io/ansible/role/d/59413)](https://galaxy.ansible.com/lotusnoir/system_local_users)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/59413)](https://galaxy.ansible.com/lotusnoir/system_local_users)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

Configure local system users

## Requirements

none

## Role variables

See [variables](/defaults/main.yml) for more details.

## Examples

        ---
        - hosts: system_local_users
          become: true
          become_method: sudo
          gather_facts: true
          roles:
            - role: ansible-system_local_users


## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

## Author Information

- [Philippe LEAL](https://github.com/lotusnoir)
