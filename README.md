[![License](https://img.shields.io/badge/license-Apache%202-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0)
[![CI](https://github.com/grycap/ansible-role-chronos/actions/workflows/main.yaml/badge.svg)](https://github.com/grycap/ansible-role-chronos/actions/workflows/main.yaml)

Chronos Role
============

Install Chronos for a Mesos cluster (recipe for EC3)

Example Playbook
----------------
```
  - hosts: server
  roles:
  - { role: 'grycap.chronos'}
```
```
  - hosts: client
  roles:
  - { role: 'grycap.chronos'}
```

Contributing to the role
========================
In order to keep the code clean, pushing changes to the master branch has been disabled. If you want to contribute, you have to create a branch, upload your changes and then create a pull request.  
Thanks
