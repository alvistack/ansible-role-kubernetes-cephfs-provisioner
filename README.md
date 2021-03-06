# Ansible Role for CephFS Volume Provisioner on Kubernetes

[![Travis](https://img.shields.io/travis/com/alvistack/ansible-role-kubernetes_cephfs_provisioner.svg)](https://travis-ci.com/alvistack/ansible-role-kubernetes_cephfs_provisioner)
[![GitHub release](https://img.shields.io/github/release/alvistack/ansible-role-kubernetes_cephfs_provisioner.svg)](https://github.com/alvistack/ansible-role-kubernetes_cephfs_provisioner)
[![GitHub license](https://img.shields.io/github/license/alvistack/ansible-role-kubernetes_cephfs_provisioner.svg)](https://github.com/alvistack/ansible-role-kubernetes_cephfs_provisioner/blob/master/LICENSE)
[![Ansible Role](https://img.shields.io/badge/galaxy-alvistack.kubernetes_cephfs_provisioner-blue.svg)](https://galaxy.ansible.com/alvistack/kubernetes_cephfs_provisioner)

**[DEPRECATED] No longer recommended for Kubernetes 1.16+, use csi-cephfs instead.**

Ansible Role for CephFS Volume Provisioner on Kubernetes Installation.

## Requirements

This role require Ansible 2.9 or higher.

This role was designed for Ubuntu 16.04/18.04/19.10 or RHEL/CentOS 7 or openSUSE Leap 15.1.

## Role Variables

[defaults/main.yml](defaults/main.yml)

## Dependencies

[meta/main.yml](meta/main.yml)

## Example Playbook

[molecule/default/converge.yml](molecule/default/converge.yml)

## License

  - Code released under [Apache License 2.0](LICENSE)
  - Docs released under [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/)

## Author Information

  - Wong Hoi Sing Edison
      - <https://twitter.com/hswong3i>
      - <https://github.com/hswong3i>
