Ansible Role: .Net Core SDK/Runtime 
=========

[![Build Status](https://travis-ci.org/ocha/ansible-role-dotnet-core.svg?branch=master)](https://travis-ci.org/ocha/ansible-role-dotnet-core)
[![Ansible Galaxy](https://img.shields.io/ansible/role/15673.svg)](https://galaxy.ansible.com/ocha/dotnet-core)

Installs the [.Net Core SDK/Runtime](https://www.microsoft.com/net) for Ubuntu/RHEL/CentOS.

Requirements
------------

This role only runs on Ubuntu, RHEL and its derivatives.

Role Variables
--------------

Available variables are listed below, along with default values (see `defaults/main.yml`):

    dotnet_rhel_url: "https://go.microsoft.com/fwlink/?LinkID=835016"
    dotnet_ubuntu_package: "dotnet-dev-1.0.0-preview2-1-003177"
    
Generally, these should not be changed, but if this role is out of date, or if you need a very specific version, these can be overridden.

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - ocha.dotnet-core

License
-------

MIT / BSD

Author Information
------------------

This role was created by [Iuri Gagnidze](https://www.github.com/ocha)
