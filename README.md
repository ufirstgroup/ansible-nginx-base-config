ansible-nginx-base-config
=========================

Ansible role for installing nginx and providing some default config files.

Role Variables
--------------

see defaults/main.yml

Requirements
-----------

Ubuntu >= 14.04, must be run as root

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
      become: yes
      roles:
        - { role: jlgeering.nginx-base-config, nginx_base_config_replace: true }

License
------

MIT

Author Information
----------------
Jean-Luc Geering

[GitHub project page](https://github.com/ufirstgroup/ansible-nginx-base-config)
