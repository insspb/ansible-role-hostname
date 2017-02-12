Ansible Role: Hostname
=========
| Master branch | Developer branch | 
|:---:|:---:|
| Master branch: [![Build Status](https://travis-ci.org/insspb/ansible-role-hostname.svg?branch=master)](https://travis-ci.org/insspb/ansible-role-hostname) | Developer branch: [![Build Status](https://travis-ci.org/insspb/ansible-role-hostname.svg?branch=develop)](https://travis-ci.org/insspb/ansible-role-hostname) |

Versions:
------------
##### v3.0: Non root user support
- Non root user support added. (become)
- Now it is possible to set system hostname different from **inventory_hostname**
- Added some missed default host names from **CentOS 6/7**
- Playbook syntax cleanup
- Meta file update
- Manual tests done on:
  - CentOS 6.8 x64
  - CentOS 6.8 x32
  - CentOS 7.3 x64
  - Debian 8.7.1 x32
  - Debian 8.7.1 x64
  - Ubuntu 14.04 x32
  - Ubuntu 14.04 x64
  - Ubuntu 16.04 x64
  - Ubuntu 16.04 x64

##### v2.1: Some changes in look of readme
- Readme updated to look good at ansible.galaxy
- Meta file cleanup

##### v2.0: New OS support
- Debian support
- CentOS support
- Variables for hosts file.

##### v1.0: First release. Publishing to Ansible Galaxy.
 - Ubuntu support, tests passed
