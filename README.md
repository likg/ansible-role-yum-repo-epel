[![Ansible Galaxy](https://img.shields.io/badge/role-likg.yum--repo--epel-blue.svg?style=flat)](https://galaxy.ansible.com/likg/yum-repo-epel/)
[![Build Status](https://travis-ci.org/likg/ansible-role-yum-repo-epel.svg?branch=master)](https://travis-ci.org/likg/ansible-role-yum-repo-epel)

# Ansible Role: EPEL YUM repo

Install EPEL YUM repo on RHEL/CentOS servers.

You can install EPEL by running yum install epel-release. The package is included in the CentOS Extras repository, enabled by default.

## Requirements

No special requirements.

## Role Variables

Available variables/default values can be found in [defaults/main.yml](defaults/main.yml).

## Dependencies

None.

## Example Playbook

    - hosts: servers
      become: yes
      roles:
        - { role: likg.yum-repo-epel }

## License

MIT

## Author Information

This role was created by Lik.
