EPEL
====

Variables
---------

### Global Variables
No global variables are used in this role.

### Role Variables
No role variables are used in this role.

### User Variables
No user-defined variables are used in this role.


Tasks
-----

### Description
This role installs the EPEL repository for use in RHEL systems.

### Changed Files
- /etc/yum.repos.d/epel.repo
- /etc/pki/rpm-gpg/RPM-GPG-KEY-EPEL-7

### Installed Programs
No installed programs.


Example
-------

### playbooks/elrepo_nvidia.yml

    ---
    - name: EPEL Ansible Playbook
      hosts: all
      user: root
      connection: smart

      roles:
        - epel