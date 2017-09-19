update-everything
=========
Extremely simple Ansible role to safely upgrade all packages on a Debian system.
Will update the apt cache as well, if necessary.
If `ansible_distribution == 'Debian'`, then `sudo` will be installed, as well.

Requirements
------------

A Debian-based system with `apt` installed.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: update-everything }

License
-------

MIT

