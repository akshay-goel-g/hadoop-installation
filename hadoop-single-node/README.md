Role Name
=========

Install hadoop on single node

Requirements
------------

python should be install and java >= 8 should be present, if java is not present or java <8 version you can uncomment java.yml in tasks/main.yml to install java 11. 

Role Variables
--------------

The hadoop user is created with default password "hadoop", you can change the hadoop user password in tasks/adduser.yml.

Example Playbook
----------------

    - hosts: hadoop
      roles:
         - hadoop-single-node

License
-------

BSD


