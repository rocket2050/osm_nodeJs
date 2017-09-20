Role Name
=========

This role setups the required dependencies and npm and nodejs packages.

Requirements
------------
None

Role Variables
--------------

None

Dependencies
------------
None

Example Playbook
----------------

```
- hosts: "{{ host }}"
  roles:
     - { role: osm_nodejs }
```

How to run the Playbook
-----------------------

- For CentOS

ansible-playbook -i hosts(your host file) site.yml 

- For Ubuntu

ansible-playbook -i hosts(your host file) site.yml 


License
-------

BSD
