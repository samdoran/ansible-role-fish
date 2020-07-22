Fish
=========
[![Galaxy](https://img.shields.io/badge/galaxy-samdoran.fish-blue.svg?style=flat)](https://galaxy.ansible.com/samdoran/fish)
[![Build Status](https://travis-ci.com/samdoran/ansible-role-fish.svg?branch=master)](https://travis-ci.com/samdoran/ansible-role-fish)

Install [Fish Shell](https://fishshell.com)

Requirements
------------

An open mind. 😉
If running this role against macOS, Homebrew must be installed.

Role Variables
--------------

| Name              | Default Value       | Description          |
|-------------------|---------------------|----------------------|
| `fish_release_version` | `3` | Major version of `fish` to install. Valid values are 2 or 3. |


Dependencies
------------

None

Example Playbook
----------------

    - hosts: all
      roles:
         - samdoran.fish

License
-------

Apache 2.0
