nginx-role
=========

This role install NGINX on specifed host


Dependencies
------------

This role is related to the lighthouse-role. Both roles install to the same host.
Template lighthouse.conf.j2 change default conf nginx.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: nginx-role }

License
-------

MIT

Author Information
------------------

Aleksandr Molokov
