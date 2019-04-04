# Ansible role: Kodi

Ansible role for installing Kodi media server on Ubuntu server 18.04

## Requirements

Setting ansible python interpreter to python3.

## Dependencies

None.

## Example playbook

    - hosts: all
      roles:
        - { role: dragomirr.kodi, ansible_python_interpreter: /usr/bin/python3 }

## Licence

GPLv3
