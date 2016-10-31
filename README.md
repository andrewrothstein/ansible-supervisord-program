andrewrothstein.supervisord-program
=========

Template role for installing a program within supervisord

Requirements
------------

See (meta/main.yml)[meta/main.yml]

Role Variables
--------------

See (defaults/main.yml)[defaults/main.yml]

Dependencies
------------

See (meta/main.yml)[meta/main.yml]

Example Playbook
----------------

Derivations of this role should be instanced.

    - hosts: servers
      roles:
         - andrewrothstein.emacs-daemon-supervisord

License
-------

MIT

Author Information
------------------

Andrew Rothstein andrew.rothstein@gmail.com
