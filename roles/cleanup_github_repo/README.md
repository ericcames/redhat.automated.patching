cleanup_github_repo
=========

This role will clean up are old insights cve remediation playbooks

Requirements
------------
```yaml
Access to the github repo
```
Role Variables
--------------
```yaml
github_repo_software_repository: https://{{ cleanup_github_repo_personal_access_token }}@github.com/ericcames/RedHatInsightsPlaybooks.git
cleanup_github_repo_local_repo: /var/tmp/github/RedHatInsightsPlaybooks
cleanup_github_repo_git_name: ericcames
cleanup_github_repo_git_email: ericcames@msn.com
cleanup_github_repo_personal_access_token: git_hub_token
```
Dependencies
------------

Example Playbook
----------------
```yaml
---
- name: Cleaning our repo
  hosts: localhost
  connection: local

  roles:

    - name: cleanup_github_repo
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
