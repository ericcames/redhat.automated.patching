get_aws_instance_info
=========

This role will get all AWS Machine Instance Info.

Requirements
------------
```yaml
Amazon Web Console Account
Amazon Web Services Credential in Ansible Automation Platform
```
Role Variables
--------------
```yaml
get_aws_instance_info_region: us-west-1
get_aws_instance_info_servername: Linux Demo Server
get_aws_instance_info_my_email_address: eames@redhat.com
```
Dependencies
------------
```yaml
amazon.aws
```
Example Playbook
----------------
```yaml
---
- name: Get Amazon Machine info
  hosts: localhost
  connection: local

  roles:

    - name: get_aws_instance_info
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
