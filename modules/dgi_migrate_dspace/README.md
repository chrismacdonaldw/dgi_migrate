# DGI Migrate DSpace

## Introduction

A module which provides the migrations for importing [AIP](https://wiki.lyrasis.org/display/DSDOC6x/DSpace+AIP+Format) 5.5 ZIPs, using a METS/MODS mapping.

It also provides a single command, `dgi_migrate_dspace:list`, which simply outputs a CSV formatted list of each node ID and URL, and its respective handle URL.

## Requirements

This module requires the following modules/libraries:

* [migrate](https://www.drupal.org/project/migrate)
* [dgi_migrate](https://github.com/discoverygarden/dgi_migrate)

## Usage

The migration can be run using the `dspace_to_dgis` migration group.

For running the command, use `dgi_migrate_dspace:list`, and provide the optional `--uri` flag for your respective environment.

## Installation

Install as usual, see
[this](https://drupal.org/documentation/install/modules-themes/modules-8) for
further information.

## Troubleshooting/Issues

Having problems or solved a problem? Contact
[discoverygarden](http://support.discoverygarden.ca).

## Maintainers/Sponsors

Current maintainers:

* [discoverygarden](http://www.discoverygarden.ca)

## Development

If you would like to contribute to this module create an issue, pull request
and or contact
[discoverygarden](http://support.discoverygarden.ca).

## License

[GPLv3](http://www.gnu.org/licenses/gpl-3.0.txt)