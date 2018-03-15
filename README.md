Role Name
=========

This role installs applications that most gamers use. This role for the moment concentrates on fedora but, it can be expanded for other distros.
Requirements
------------


Role Variables
--------------
```
dev_work:
   rpms:
     - 
     - 
     - 
     - 
   pip:
     - virtualenv
  ruby_gems:
      - chef
      - rbenv
  virtualenvs:
  - venv1:
      path: /root/venv1
      packages:
        - ansible
        - requests
  - venv2
      path: /home/mike/venv2
      packages:
         - fabric
```

Dependencies
------------


Example Playbook
----------------

    - hosts: all
      roles:
         - gaming_desktop 

License
-------

Apache V2

Author Information
------------------
Linux Gamers (jlozada2426@protonmail.com).
