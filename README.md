nip.io-wildcard-dns
========

Installs and configure powerdns and nip.io to serve as wildcard DNS for any IP address

Requirements
------------

This role requires Ansible 2.2 or higher.

Role Variables
--------------

Edit `group_vars/all/main.yaml`.

For details see:
[ansible-nip.io README.md](https://github.com/gites/ansible-nip.io/blob/master/README.md)
[ansible-powerdns README](https://github.com/gites/ansible-powerdns/blob/master/README.md)

Dependencies
------------

None

Example Run
----------------

```shell
ansible-playbook -i localhost, site.yaml -s
```

License
-------

Apache 2.0

Author Information
------------------

Gites
