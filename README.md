easyrsa-ca
=========

[![Build Status](https://travis-ci.org/vduseev/ansible-role-easyrsa-ca.svg?branch=master)](https://travis-ci.org/vduseev/ansible-role-easyrsa-ca)

This role sets up a certificate authority using easyrsa binary available in the PATH. The CA is set up without a password and with default EasyRSA values for the CN fields.

Dependencies
------------

The role depends on `vduseev.easyrsa` role.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```
- hosts: servers
  roles:
    - vduseev.easyrsa-ca
```

License
-------

MIT
