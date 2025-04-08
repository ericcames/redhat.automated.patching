get_insights_inventory_id
=========

This role will get the insights instance id from console.redhat.com

Requirements
------------
```yaml
Red Hat Hybrid Cloud Console account
RHEL Servers with Insights client enabled
```
console.redhat.com

Role Variables
--------------
```yaml
insights_username: foobar
insights_password: secret_does_not_go_here
```
Dependencies
------------

Example Playbook
----------------
```yaml
---
- name: Get an insights instance id
  hosts: localhost
  connection: local

  roles:

    - name: get_insights_inventory_id
```
License
-------

https://spdx.org/licenses/MIT.html

Author Information
------------------
```yaml
Eric C Ames
```
ericcames@msn.com
