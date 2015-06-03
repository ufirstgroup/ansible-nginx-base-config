ansible-nginx-base-config
=========================

Ansible role for installing nginx and providing some default config files.

Role Variables
--------------

see defaults/main.yml

Requirements
-----------

Ubuntu >= 14.04

Dependencies
-----------

none

Installation
----------

    ansible-galaxy install jlgeering.nginx-base-config

Example Playbook
----------------

    ---
    - hosts: all
      roles:
        - { role: jlgeering.nginx-base-config, nginx_base_config_cleanup: false }

License
------

MIT

Author Information
----------------
Jean-Luc Geering

[GitHub project page](https://github.com/ufirstgroup/ansible-nginx-base-config)
