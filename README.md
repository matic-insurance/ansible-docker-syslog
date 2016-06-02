docker-syslog
=========

Make Docker write its logs to syslog.

Syslog is more flexible in stuff like log rotation and remote logging.

Requirements
------------

This role is only for Ubuntu/Debian-based systems.
It relies on `/etc/default/docker` configuration file

Role Variables
--------------

No variables

Dependencies
------------

No dependencies

Example Playbook
----------------

Just include this role as in example:

    - hosts: all
      roles:
         - role: matic-insurance.docker-syslog

License
-------

MIT

Author Information
------------------

Matic is a communication platform that connects lenders and borrowers originating a new home loan. A borrower now knows where they are in the loan process and what they need to do to complete the loan.
