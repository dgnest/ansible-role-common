# Ansible Role Common

<span class="badges" align="center">
[![GitHub tag](https://img.shields.io/github/tag/dgnest/ansible-role-common.svg?maxAge=2592000)](https://github.com/dgnest/ansible-role-common)
[![Build Status](https://travis-ci.org/dgnest/ansible-role-common.svg)](https://travis-ci.org/dgnest/ansible-role-common)
[![GitHub issues](https://img.shields.io/github/issues/dgnest/ansible-role-common.svg)](https://github.com/dgnest/ansible-role-common/issues)
[![GitHub license](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square)](LICENSE)
</span>


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
         - { role: dgnest.common }


## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Credits

Made with :heart: ️:coffee:️ and :pizza: by [dgnest][link-company].

- [All Contributors][link-contributors]


<!-- Other -->

[link-luis]: https://github.com/luismayta
[link-contributors]: AUTHORS
[link-company]: https://github.com/dgnest
