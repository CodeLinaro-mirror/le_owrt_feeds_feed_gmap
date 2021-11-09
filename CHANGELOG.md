# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]


## Release v0.8.3 - 2021-11-09(08:47:08 +0000)

### Changes

- [gmap-mod-self](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-self): remove symlink to init script
- [gmap-mod-ethernet-dev](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-ethernet-dev): remove symlink to init script

## Release v0.8.2 - 2021-10-14(11:25:18 +0000)

## Release v0.8.1 - 2021-10-06(11:42:29 +0000)

### Fixes

- [gmap-mod-self](https://gitlab.com/soft.at.home/gmap/applications/gmap-mod-self): [GMAP-MOD-SELF] add ; in odl
- [gmap-mod-self](https://gitlab.com/soft.at.home/gmap/applications/gmap-mod-self): [GMAP-MOD-SELF] wait for network.device on ubus

## Release v0.8.0 - 2021-09-15(07:36:35 +0000)

### New

- [gmap-mod-ethernet-dev](https://gitlab.com/soft.at.home/gmap/applications/gmap-mod-ethernet-dev): make use of libdhcpoption

## Release v0.7.1 - 2021-09-14(16:27:08 +0000)

### Fixes

- [gmap-mibs-common](https://gitlab.com/soft.at.home/gmap/mibs/gmap-mibs-common): [amxc] add ifdef around when_null_x, when_str_empty_x
- [gmap-mibs-common](https://gitlab.com/soft.at.home/gmap/mibs/gmap-mibs-common): Use amxc_macros.h instead of local macros
- [gmap-mod-name-selector](https://gitlab.com/soft.at.home/gmap/applications/gmap-mod-name-selector): [amxc] add ifdef around when_null_x, when_str_empty_x

## Release v0.7.0 - 2021-08-20(14:14:49 +0000)

### New

- [gmap-server](https://gitlab.com/soft.at.home/gmap/applications/gmap-server): [GMAP] add implementation for name selection

## Release v0.6.0 - 2021-08-18(17:16:12 +0000)

### New

- [gmap-mod-name-selector](https://gitlab.com/soft.at.home/gmap/applications/gmap-mod-name-selector): Component added
- [gmap-mod-ethernet-dev](https://gitlab.com/soft.at.home/gmap/applications/gmap-mod-ethernet-dev): GMAP-MOD-ETHERNET-DEV add dhcp information to device

### Fixes

- [libgmap-client](https://gitlab.com/soft.at.home/gmap/libraries/libgmap-client): [GMAP_CLIENT] functions returns array while expecting a bool
- [libgmap-client](https://gitlab.com/soft.at.home/gmap/libraries/libgmap-client): [GMAP-CLIENT] gmap_device_hasTag does not work
- [gmap-server](https://gitlab.com/soft.at.home/gmap/applications/gmap-server): [GMAP-SERVER] allow hasTags to check multiple tags

## Release v0.5.2 - 2021-08-06(13:58:03 +0000)

### Changes

- [gmap-server](https://gitlab.com/soft.at.home/gmap/applications/gmap-server): GMAP-SERVER update mibs after changing tag

## Release v0.5.1 - 2021-08-05(14:40:46 +0000)

### Fixes

- [libgmap-client](https://gitlab.com/soft.at.home/gmap/libraries/libgmap-client): Circular dependency libgmap-client and gmap-server

