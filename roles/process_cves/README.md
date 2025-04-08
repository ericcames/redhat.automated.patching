process_cves
=========

This role will patch cves on target machine

Requirements
------------
```yaml
RHEL Servers with Insights client enabled
Software repo with token
```
Role Variables
--------------
```yaml
process_cves_software_repository: https://{{ process_cves_personal_access_token }}@github.com/ericcames/RedHatInsightsPlaybooks.git
process_cves_personal_access_token: git_hub_token
process_cves_local_repo: /var/tmp/github/RedHatInsightsPlaybooks
process_cves_git_name: ericcames
process_cves_git_email: ericcames@msn.com
process_cves_job_template_id: 222
process_cves_project_id: 221
```
Dependencies
------------
```yaml
```
Example Playbook
----------------
```yaml
---
- name: Process CVES
  hosts: localhost
  connection: local

  roles:

    - name: process_cves
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
