[![GloboDNS](https://img.shields.io/badge/Ansible%20Galaxy-Globo%20DNS-blue.svg)](https://galaxy.ansible.com/wluisaraujo/iac-ansible-globodns)  [![Build Status](https://travis-ci.org/wluisaraujo/iac-ansible-globodns.svg?branch=master)](https://travis-ci.org/wluisaraujo/iac-ansible-globodns)

---
# IaC: with [Ansible](https://www.ansible.com) role to install and configure [GloboDNS](https://github.com/globocom/GloboDNS)
------------

Description
------------
 * GloboDNS Web GUI for Bind

Requirements
------------

 *

Installation
------------

```console
vagrant@localhost:~$ ansible-galaxy install wluisaraujo.globodns
```

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
    - globodns
...
```

----------------
[![Licence](https://img.shields.io/badge/License-GPL%20v3-red.svg)](https://www.gnu.org/licenses/gpl-3.0.pt-br.html)
