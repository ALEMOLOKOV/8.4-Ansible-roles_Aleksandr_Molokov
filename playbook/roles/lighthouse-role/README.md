lighthouse-role
=========

This role install lighthouse to the specified host.

Requirements
------------

Installation implements via git, so at start in pre_task will be install module git 


Dependencies
------------

This role related to nginx-role for this playbook, role create nginx config  for lighthouse according template.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: lighthouse
      roles:
         - { role: lighthouse-role }

License
-------

MIT

Author Information
------------------

Aleksandr Molokov
