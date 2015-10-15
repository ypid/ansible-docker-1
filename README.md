## [![DebOps project](http://debops.org/images/debops-small.png)](http://debops.org) docker

[![Travis CI](http://img.shields.io/travis/debops/ansible-docker.svg?style=flat)](http://travis-ci.org/debops/ansible-docker) [![test-suite](http://img.shields.io/badge/test--suite-ansible--docker-blue.svg?style=flat)](https://github.com/debops/test-suite/tree/master/ansible-docker/)  [![Ansible Galaxy](http://img.shields.io/badge/galaxy-debops.docker-660198.svg?style=flat)](https://galaxy.ansible.com/list#/roles/5015)

[Docker](https://docker.com/) is a lightweight virtualization platform
based on Linux kernel features that allow creation and management of
isolated application environments.

### Installation

This role requires at least Ansible `v1.9.0`. To install it, run:

    ansible-galaxy install debops.docker

### Documentation

More information about `debops.docker` can be found in the
[official debops.docker documentation](http://docs.debops.org/en/latest/ansible/roles/ansible-docker/docs/).


### Role dependencies

- `debops.ferm`
- `debops.etc_services`

### Are you using this as a standalone role without DebOps?

You may need to include missing roles from the [DebOps common
playbook](https://github.com/debops/debops-playbooks/blob/master/playbooks/common.yml)
into your playbook.

[Try DebOps now](https://github.com/debops/debops) for a complete solution to run your Debian-based infrastructure.





### Authors and license

`docker` role was written by:
- Maciej Delmanowski | [e-mail](mailto:drybjed@gmail.com) | [Twitter](https://twitter.com/drybjed) | [GitHub](https://github.com/drybjed)

License: [GPLv3](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

***

This role is part of the [DebOps](http://debops.org/) project. README generated by [ansigenome](https://github.com/nickjj/ansigenome/).