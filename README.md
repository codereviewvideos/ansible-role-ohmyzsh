Role Name
=========

Installs ohmyzsh for any users configured with the mivok0 users role. Ideally don't use standalone, currently. 

Not customisable at the moment, but open to PR's to improve this.

Requirements
------------

Requires mivok0 users role, and git. 

Role Variables
--------------

None.

Dependencies
------------

mivok0 users role.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

- hosts: all
  sudo: True

  roles:
    - linux-core-software # install git somehow
    - users
    - ohmyzsh

 License
 -------

 BSD

 Author Information
 ------------------

 Chris - https://codereviewvideos.com/
