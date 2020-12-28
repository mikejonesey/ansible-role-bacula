Role Name
=========

This role sets up the basic requirements for a bacula server. It is intended to be run on a Debian target. Baculum will web server will also be setup, which can be used to configure the dir and storage (just jump into bconsole to spawn some volumes).

Requirements
------------

A debian host or VM that meets the minumum system requirements of bacula.

Role Variables
--------------

todo...

Dependencies
------------

no other roles are required.

Example Playbook
----------------

Bacula servers are expected to be placed within a group called: "bacula"

    - hosts: bacula
      become: yes
      roles:
        - bacula
      tags: bacula

License
-------

BSD

Author Information
------------------

Michael Jones <mj@mikejonesey.co.uk>
