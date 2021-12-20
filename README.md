Role Name
=========

A simple Ansible Role to set the Gnome Shell touchpad settings

Example Playbook
----------------

Playbook "user-config.yml"

    - hosts: localhost
      roles:
      - dotmjs.gnome_shell_touchpad_tweaks

Invocation

    ansible-playbook -i localhost --ask-become-pass user-config.yml

License
-------

Apache 2.0

Author Information
------------------
MJS
