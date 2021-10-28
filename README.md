AWS CLI Tools
=========

This role installs the AWS CLI Tools using Python pip.

[![Build Status](https://github.com/Rheinwerk/ansible-role-awscli/actions/workflows/ci.yml/badge.svg)](https://github.com/Rheinwerk/ansible-role-awscli/actions/workflows/ci.yml)

Requirements
------------

Python and pip must be installed.

Role Variables
--------------

No variables.

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: awscli, tags: [ 'awscli' ] }

License
-------

Please see LICENSE.

Author Information
------------------

Original author is [Daniel Schneller](https://github.com/dschneller) as member of the [Rheinwerk](https://github.com/Rheinwerk) project.


