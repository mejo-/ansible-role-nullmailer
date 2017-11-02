# Ansible role to install nullmailer

[![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-nullmailer-blue.svg)](https://galaxy.ansible.com/mejo-/nullmailer/) [![Build Status](https://travis-ci.org/mejo-/ansible-role-nullmailer.svg?branch=master)](https://travis-ci.org/mejo-/ansible-role-nullmailer)

A very simple role to install and configure nullmailer on Debian.

It will completely remove other MTA packages.

# Defaults

```
mail_admin_address: "admin@{{ domain }}"
#mail_relays: []

nullmailer_mta_pkgs:
  - exim4
  - exim4-base
  - exim4-config
  - exim4-daemon-light
  - exim4-daemon-heavy
  - postfix
```

# License

This Ansible role is licensed under the GNU GPLv3 or later.

# Author

Copyright 2017 Jonas Meurer <jonas@freesources.org>
