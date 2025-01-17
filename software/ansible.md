---
title: Ansible
developerlink: http://www.ansible.com
licensingmodel: open source
license: Apache
logo: /100px-Ansible_logo.svg.png
tags:
- infrastruktur
---
__Ansible__ is a free automation tool for orchestration and configuration and administration of servers.

---

We use Ansible for numerous _infrastructure as code_ automations, for example, our [Openshift](openshift.html) is rolled out and updated fully automatically with the ansible role [ansible-openshift4-vmware/](https://github.com/it-at-m/ansible-openshift4-vmware/).

### AWX

We operate an [AWX](https://github.com/ansible/awx) for the central service desk, which automatically rolls out all standard tasks in our data centers using Ansible playbooks.
This includes the provision of virtual servers, databases, storage, domains and the assignment of temporary user rights.
Together with the free [Katello](/software/katello), AWX forms our central system management.
