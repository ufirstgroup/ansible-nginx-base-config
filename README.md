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

Ubuntu >= 14.04

Installation
----------

    ansible-galaxy install jlgeering.nginx-base-config

example playbook:

    ---
    - hosts: all
      vars:
        nginx_base_config_cleanup: false
      roles:
        - jlgeering.nginx-base-config

License
------

MIT

Author Information
----------------
Jean-Luc Geering

[GitHub project page](https://github.com/ufirstgroup/ansible-nginx-base-config)
