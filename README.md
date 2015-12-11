# Ansible Role Common

<span class="badges" align="center">
[![Build Status](https://travis-ci.org/dgnest/ansible-role-common.svg)](https://travis-ci.org/dgnest/ansible-role-common)
[![Stories in Ready](https://badge.waffle.io/dgnest/ansible-role-common.svg?label=ready&title=Ready)](http://waffle.io/dgnest/ansible-role-common)
[![GitHub issues](https://img.shields.io/github/issues/dgnest/ansible-role-common.svg)](https://github.com/dgnest/ansible-role-common/issues)
[![GitHub license](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square)](LICENSE)
</span>


Installs and configures [common][link-common] on a host.

## Requirements

 - Linux
   - none
 - OSX
   - none


## Role Variables

The default role variables in `defaults/main.yml` are:

    ---
    # defaults file for common


## Dependencies

none

## Example Playbook

See the [examples](./examples/) directory.

To run this playbook with default settings, create a basic playbook like this:

    - hosts: servers
      roles:
         - common

To install a specific version:

    - hosts: servers
      roles:
         - { role: luismayta.common }


## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Credits

- [Luis Mayta][link-luis]
- [All Contributors][link-contributors]


<!-- Other -->

[link-luis]: https://github.com/luismayta
[link-contributors]: contributors
