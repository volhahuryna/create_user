create_user
=========

Create a user and upload an ssh public key for remote authentication

Requirements
------------

No specific required Ansible
Need a default ssh public key or a specific key needs to be called out in a variable

Role Variables
--------------
#Define the user ypu would like to create
user_name: default

#Define the user state present or absent
user_state: present

#Define the path to the ssh public key
ssh_key: ~/.ssh/id_rsa.pub

Dependencies
------------

None

Example Playbook
----------------


License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
