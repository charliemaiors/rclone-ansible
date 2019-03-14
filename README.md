Ansible Rclone
=========

[![Build Status](https://travis-ci.org/charliemaiors/rclone-ansible.svg?branch=master)](https://travis-ci.org/charliemaiors/rclone-ansible)

This role will install [Rclone](https://rclone.org/) for:

* Archlinux
* CentOS/RHEL
* Debian/Ubuntu
* Fedora
* FreeBSD
* macOS
* OpenSUSE
* Windows

Requirements
------------

There are no particular requirements, only the standards for FreeBSD and Windows connection setting.

Role Variables
--------------

No variables ATM.

Dependencies
------------

None

Example Playbook
----------------

Simple and easy

    - hosts: rclone
      roles:
         - { role: charliemaiors.rclone-ansible }

License
-------

BSD

Notes
-------

The unsupported part was taken from [stefangweichinger.ansible-rclone](https://github.com/stefangweichinger/ansible-rclone)
