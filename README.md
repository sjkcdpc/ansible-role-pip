pip
=========

This role install pip and configure repository mirror.

Role Variables
--------------

    pip_index_url: http://mirrors.aliyun.com/pypi/simple/
    pip_trusted_host: mirrors.aliyun.com

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: mds1455975151.ansible-role-pip, x: 42 }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
