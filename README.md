# jtprogru.macos

![GitHub Workflow Status](https://img.shields.io/github/workflow/status/jtprogru/ansible-role-macos/CI?label=CI)
![GitHub Workflow Status](https://img.shields.io/github/workflow/status/jtprogru/ansible-role-macos/Release?label=Release)
![GitHub](https://img.shields.io/github/license/jtprogru/ansible-role-macos)
[![Ansible Role](https://img.shields.io/ansible/role/54364)](https://galaxy.ansible.com/jtprogru/macos/)
[![GitHub tag](https://img.shields.io/github/tag/jtprogru/ansible-role-macos.svg)](https://github.com/jtprogru/ansible-role-macos/tags)

This is sample ansible role used me as boilerplate.


## Role Variables


See [`defaults/main.yml`](defaults/main.yml).


## Example Playbook

Example playbook:
```yaml
---
- name: macOS
  hosts: localhost
  connection: local
  become: false
  gather_facts: true

  vars:
    macos_hostname: "cronus"
    macos_homebrew_tap_ext:
      - coreutils
      - ghc

  roles:
    - jtprogru.macos
```

## Author

Michael Savin aka `@jtprogru`

Twitter: [![Twitter Follow](https://img.shields.io/twitter/follow/jtprogru?color=gree&style=plastic)](https://twitter.com/jtprogru/)

## License

See [LICENSE](LICENSE)
