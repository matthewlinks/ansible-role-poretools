Role Name
=========

This is a role that will ensure the dependancies are configured and then install poretools from https://github.com/arq5x/poretools.
For more information on poretools see http://poretools.readthedocs.io/en/latest/

Requirements
------------

This role is designed for CentOS || RHEL servers. It uses yum for package management. There is a need to install the EPEL repository for the some of the poretools dependencies like HDF5. 

Role Variables
--------------

There are no variables. 

Dependencies
------------

There are no dependancies.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: NanoporeAnalysisServers
      roles:
         - { role: matthewlinks.poretools }

License
-------

CC-BY

Author Information
------------------

http://www.coadunate.net/
