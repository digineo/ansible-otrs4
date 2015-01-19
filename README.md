OTRS 4
=========

Installs [OTRS 4](https://www.otrs.com/) on a Debian/Ubuntu host with PostgreSQL.

Role Variables
--------------

The following variables are defaults an can be overridden:

    otrs_version: 4.0.4

Example Playbook
----------------

    - hosts: servers
      roles:
      - { role: otrs4, otrs_version: "4.0.4" }

License
-------

This code is licensed under [MIT license](http://opensource.org/licenses/MIT)
