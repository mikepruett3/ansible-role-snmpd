Ansible Role: SNMPD
=========

Ansible role to configure SNMP daemon on Linux Servers.

Requirements
------------

The role does not require anyting to run on RHEL and its derivatives.

Role Variables
--------------

Available variables are listed below, along with default values (see ```defaults/main.yml```):

``` yaml
snmp_username: "username"
snmp_password: "password"
```

```snmp_username``` **(Required)** The SNMPv3 username to configure.

```snmp_password``` **(Required)** The cooresponding password for the SNMPv3 username.

Role variables can be stored with the hosts.yaml file, or in the main variables file.

Dependencies
------------

None.

Example Playbook
----------------

``` yaml
    - hosts: servers
      roles:
         - role: mikepruett3.snmpd
```

License
-------

MIT

Author Information
------------------

Role created by [mikepruett3](https://github.com/mikepruett3) on [Github.com](https://github.com/mikepruett3/ansible-role-snmpd)
