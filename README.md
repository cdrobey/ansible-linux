Ansible Common Installation Procedure
=====================================

This repository hosts the ansible playbooks that setup a common hardened version of ubuntu 16.04

Requirements
------------

The scripts require a clearn installation of Ubuntu 16.04

	- python
	- aptitude 

Roles
-----

The site.yml ansible playbook references a series of roles to support the deployment of the various roles.

* apt - Load consistent packages
* timezone - Set timezone

License
-------

BSD

Author Information
------------------

The common playbook is available for forking or general use. cdr67@yahoo.com or @cdrobey
