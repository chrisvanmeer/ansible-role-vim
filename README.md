Role Name
=========

An ansible role to install my preferred vim settings.

Requirements
------------

Vim installed.

Role Variables
--------------

| Variable | Default Value | Description|
| -- | -- | -- |
| vim_home_path | `~` | Defaults to the current user directory. |

Dependencies
------------

Not really a dependency, but for myself I use this in conjunction with `chrisvanmeer.dotfiles`.


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: localhost
      roles:
         - role: chrisvanmeer.vim

License
-------

MIT