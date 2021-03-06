<p><img src="https://wiki.jenkins-ci.org/download/attachments/2916393/logo-title.png?version=1&modificationDate=1302753947000&api=v2" alt="jenkins logo" title="jenkins" align="right" height="60" /></p>

Ansible Role: jenkins
===================

This repository is no longer maintained and we won't accept any PRs.
--------------------------------------------------------------------

[![Build Status](https://travis-ci.org/SoInteractive/ansible-jenkins.svg?branch=master)](https://travis-ci.org/SoInteractive/ansible-jenkins) [![License](https://img.shields.io/badge/license-MIT%20License-brightgreen.svg)](https://opensource.org/licenses/MIT) [![Ansible Role](https://img.shields.io/ansible/role/18278.svg)](https://galaxy.ansible.com/SoInteractive/jenkins/) [![Twitter URL](https://img.shields.io/twitter/follow/sointeractive.svg?style=social&label=Follow%20%40SoInteractive)](https://twitter.com/sointeractive)

Role to install Jenkins with basic configuration (admin account, plugins, system variables)

# :warning: IMPORTANT NOTICE

THIS PROJECT IS ABANDONED. WE DO NOT ACCEPT ANY NEW ISSUES AND/OR PULL REQUESTS.

Example usage
-------------

Use it in a playbook as follows:
```yaml
- hosts: all
  become: true
  roles:
    - SoInteractive.jenkins
```

Have a look at the [defaults/main.yml](defaults/main.yml) for role variables
that can be overridden.

TODO
----

- Java for CentOS support - currently manual java installation is required to use this role.
- Loops in credentials creation to add multiple credential variables (Jinja)
