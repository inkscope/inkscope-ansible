# inkscope-ansible


Work in progress: don't use


## Purpose

This playbook intends to replace Inkscope installation from packages (deb, rpm) because we can't maintain them.

It will install Inkscope and all its dependencies directly from the Github repository.


## Pre-requisites

- Ceph must be installed on the targeted server, with the convenient ceph configuration file and admin keyring .

- vars/my_inkscope.yaml must filled with your own parameters

