[![Build Status](https://travis-ci.org/wluisaraujo/iac-ansible-globodns.svg?branch=master)](https://travis-ci.org/wluisaraujo/iac-ansible-globodns)
---
# IaC: with [Ansible](https://www.ansible.com) role to install and configure [GloboDNS](https://github.com/globocom/GloboDNS)
------------

Description
------------
 * GloboDNS Web GUI for Bind

Requirements
------------

 *

Role Variables
--------------

[defaults/main.yml](defaults/main.yml)

Dependencies
------------

* None

Example Playbook
----------------
```yaml
---
- hosts: localhost
  vars:
    - name: value
  roles:
    - iac-ansible-globodns
```

License
-------

[GPLv3](https://www.gnu.org/licenses/gpl-3.0.pt-br.html)
