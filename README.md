![Ansible Lint](https://github.com/johanneskastl/ansible-role-openwrt_list_user_installed_packages_script/workflows/Ansible%20Lint/badge.svg)

openwrt_list_user_installed_packages_script
=========

Create a script on OpenWRT to list packages that were installed by the user. The script will reside in `/usr/bin/list_user-installed_packages.sh`.

Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
        - role: 'johanneskastl.openwrt_list_user_installed_packages_script'

License
-------

BSD-3-Clause

Author Information
------------------

I am Johannes Kastl, reachable via kastl@b1-systems.de.
