Role Name
=========

Install Lighthouse with Ngnix

Requirements
------------


Role Variables
--------------

- defaults
```
lighthouse_dir: "lighthouse"
```
- vars
```
lighthouse_version: "master"
lighthouse_git: "https://github.com/VKCOM/lighthouse.git"
lighthouse_path: "/srv/www/"
```

Dependencies
------------


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
