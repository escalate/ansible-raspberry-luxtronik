[![Test](https://github.com/escalate/ansible-raspberry-luxtronik/actions/workflows/test.yml/badge.svg?branch=master&event=push)](https://github.com/escalate/ansible-raspberry-luxtronik/actions/workflows/test.yml)

# Ansible Role: Raspberry - Luxtronik

An Ansible role that manages Luxtronik statistics backup on Raspberry Pi OS (Debian Bookworm).

## Role Variables

Please see [defaults/main.yml](https://github.com/escalate/ansible-raspberry-luxtronik/blob/master/defaults/main.yml) for a complete list of variables that can be overridden.

## Dependencies

This role relies on the following dependencies:

* Roles: [requirements.yml](https://github.com/escalate/ansible-raspberry-luxtronik/blob/master/requirements.yml)
* Collections: None

## Installation

```
$ ansible-galaxy role install escalate.luxtronik
```

## Example Playbook

```
- hosts: all
  roles:
    - role: escalate.luxtronik
      tags: luxtronik
```

## License

MIT
