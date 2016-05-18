## [![DebOps project](http://debops.org/images/debops-small.png)](http://debops.org) ferm

<!-- This file was generated by Ansigenome. Do not edit this file directly but
     instead have a look at the files in the ./meta/ directory. -->

[![Travis CI](http://img.shields.io/travis/debops/ansible-ferm.svg?style=flat)](http://travis-ci.org/debops/ansible-ferm)
[![test-suite](http://img.shields.io/badge/test--suite-ansible--ferm-blue.svg?style=flat)](https://github.com/debops/test-suite/tree/master/ansible-ferm/)
[![Ansible Galaxy](http://img.shields.io/badge/galaxy-debops.ferm-660198.svg?style=flat)](https://galaxy.ansible.com/detail#/role/1565)


[ferm](http://ferm.foo-projects.org/) is a wrapper around the `iptables`
and the `ip6tables` commands which lets you manage host firewalls in an
easy and Ansible-friendly way. This role can be used to setup firewall
rules directly from the inventory, or it can be used as a dependency by
other roles to setup firewall rules for other services.

### Installation

This role requires at least Ansible `v1.7.0`. To install it, run:

```Shell
ansible-galaxy install debops.ferm
```

### Documentation

More information about `debops.ferm` can be found in the
[official debops.ferm documentation](http://docs.debops.org/en/latest/ansible/roles/ansible-ferm/docs/).



### Are you using this as a standalone role without DebOps?

You may need to include missing roles from the [DebOps common
playbook](https://github.com/debops/debops-playbooks/blob/master/playbooks/common.yml)
into your playbook.

[Try DebOps now](https://github.com/debops/debops) for a complete solution to run your Debian-based infrastructure.





### Authors and license

`ferm` role was written by:

- Maciej Delmanowski | [e-mail](mailto:drybjed@gmail.com) | [Twitter](https://twitter.com/drybjed) | [GitHub](https://github.com/drybjed)

License: [GPLv3](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

***

This role is part of the [DebOps](http://debops.org/) project. README generated by [ansigenome](https://github.com/nickjj/ansigenome/).
