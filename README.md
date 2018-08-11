bkono.pyenv
=========

Setup pyenv, with automatic installation of python versions and virtualenvs. Defaults to all users installation via /usr/local.

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

    - hosts: servers
      roles:
         - bkono.pyenv

License
-------

MIT / BSD

Author Information
------------------

This role was created by [Bryan Konowitz](https://github.com/bkono).
