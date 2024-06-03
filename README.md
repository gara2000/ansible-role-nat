NAT_SERVER
=========

Configure a server to serve as NAT for a private subnet

Requirements
------------

- No requirements

Role Variables
--------------

- private_cidr_block: The private network CIDR, for which we want to configure NAT
- primary_interface: The primary interface of the NAT server

Dependencies
------------

- No dependencies

Example Playbook
----------------

```yaml
- hosts: servers
  become: yes
  roles:
      - gara2000.nat_server
```

License
-------

MIT
