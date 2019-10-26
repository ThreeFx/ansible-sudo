sudo
=========

Install sudo and configure sudoers on Debian buster.

Requirements
------------

None.

Role Variables
--------------


| Variable Name | Default Value | Description |
--------------- |---------------|--------------
`sudo_passwordless_sudoers` | [] | Users allowed to use sudo without password
`sudo_passworded_sudoers` | [] | Users allowed to use sudo with password

Dependencies
------------

None.

Example Playbook
----------------

See `molecule/default/playbook.yml`.

License
-------

BSD

Author Information
------------------

Find me on [GitHub](https://github.com/ThreeFx).
