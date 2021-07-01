# moodle
Ansible playbook created to install moodle. Done with molecule. 
=======
Role Name
=========

Role created as an exercise to install moodle platform. Done with isntruction from: https://docs.moodle.org/311/en/Step-by-step_Installation_Guide_for_Ubuntu 

Requirements
------------

Create with ansible [core 2.11.2] for Ubuntu 18.04

Role Variables
--------------

mysql_root_pass - root mysql password
moodle_db_pass - moodle database user password

Dependencies
------------

n/a

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: anihilat.moodle, mysql_root_pass: secret, moodle_db_pass: secret }

License
-------

No license

Author Information
------------------

Anihilat
