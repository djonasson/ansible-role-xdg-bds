# Ansible Role: XDG BDS

[![CI](https://github.com/djonasson/ansible-role-xdg_bds/workflows/CI/badge.svg?event=push)](https://github.com/djonasson/ansible-role-xdg_bds/actions?query=workflow%3ACI) [![Ansible Galaxy Quality Score](https://img.shields.io/ansible/quality/57677)](https://galaxy.ansible.com/djonasson/xdg_bds/) [![Ansible Galaxy](https://img.shields.io/ansible/role/d/57677)](https://galaxy.ansible.com/djonasson/xdg_bds/) [![MIT Licence](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/djonasson/ansible-role-xdg_bds/blob/main/LICENSE)


Ansible role to configure [XDG Base Directory Specification](https://specifications.freedesktop.org/basedir-spec/basedir-spec-latest.html) shell variables and directories.

## Requirements

None.

## Role Variables

The role variables are defined in `defaults/main.yml` with these defaults:

    x: "y"

## Dependencies

None

## Example Playbook

    - hosts: localhost
      roles:
        - role: djonasson.xdg_bds

## License

MIT

## Author

This ansible role was created by [Daniel Jonasson](https://github.com/djonasson/).
