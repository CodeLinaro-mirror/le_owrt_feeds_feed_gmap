# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]


## Release v1.0.5 - 2023-03-21(13:59:29 +0000)

### Other

- [gmap-mod-ethernet-dev](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-ethernet-dev): Rename gmap_ethernet_dev_netdev->gmap_ethernet_dev_bridgetable

## Release v1.0.4 - 2023-03-15(17:35:51 +0000)

### Other

- [gmap-mod-ethernet-dev](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-ethernet-dev): Adapt to DHCPv4Server path change

## Release v1.0.3 - 2023-03-13(07:19:46 +0000)

### Other

- [libgmap-client](https://gitlab.com/prpl-foundation/components/gmap/libraries/libgmap-client): gmap config event handling: server and client side

## Release v1.0.2 - 2023-03-02(12:03:41 +0000)

### Other

- [gmap-client](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-client): [amx][gmap-client] /etc/init.d/gmap-client does nothing on non-internal build

## Release v1.0.1 - 2023-02-24(18:31:25 +0000)

### Other

- [gmap-mod-ethernet-dev](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-ethernet-dev): Provide a parameter reference to the DHCP Client Lease
- [gmap-mod-self](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-self): Fix no logging when running standalone

## Release v1.0.0 - 2023-02-23(13:52:50 +0000)

### Breaking

- [gmap-server](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-server): Change setActive API to have source and priority
- [libgmap-client](https://gitlab.com/prpl-foundation/components/gmap/libraries/libgmap-client): Adapt to new setActive API with source and priority

### Other

- [gmap-mibs-common](https://gitlab.com/prpl-foundation/components/gmap/mibs/gmap-mibs-common): Adapt to new setActive API with source and priority
- [gmap-mod-ethernet-dev](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-ethernet-dev): Adapt to 'nemo' tag not used anymore
- [gmap-mod-ethernet-dev](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-ethernet-dev): Adapt to new setActive API with source and priority
- [gmap-mod-self](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-self): Adapt to new setActive API with source and priority

## Release v0.17.11 - 2023-02-16(13:57:24 +0000)

### Other

- [gmap-server](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-server): Fix gmap-server sometimes thinks time never syncronized
- [libgmap-client](https://gitlab.com/prpl-foundation/components/gmap/libraries/libgmap-client): [libgmap-client] generated datamodel documentation is empty

## Release v0.17.10 - 2023-02-15(17:03:48 +0000)

### Other

- [gmap-mibs-common](https://gitlab.com/prpl-foundation/components/gmap/mibs/gmap-mibs-common): Rename nemo->netdev and adapt to new 'style' of mib expression
- [gmap-mod-self](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-self): Adapt to 'nemo' tag not used anymore

## Release v0.17.9 - 2023-02-08(18:19:04 +0000)

### Other

- [gmap-mibs-common](https://gitlab.com/prpl-foundation/components/gmap/mibs/gmap-mibs-common): [gMap][BDD] Create Information MiB
- [gmap-mibs-common](https://gitlab.com/prpl-foundation/components/gmap/mibs/gmap-mibs-common): [BDD][gMap] Create BDD MiB

## Release v0.17.8 - 2023-02-07(14:52:00 +0000)

### Other

- [gmap-mod-ethernet-dev](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-ethernet-dev): Mark colliding IPs with Status=error

## Release v0.17.7 - 2023-02-06(11:57:57 +0000)

### Other

- [libgmap-ext](https://gitlab.com/prpl-foundation/components/gmap/libraries/libgmap-ext): Track MAC and collisions and reduce ARPs sent

## Release v0.17.6 - 2023-02-03(20:34:43 +0000)

### Other

- [gmap-server](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-server): Fix incorrect log on adding default name
- [gmap-server](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-server): Remove event stdout spam

## Release v0.17.5 - 2023-02-02(12:33:47 +0000)

### Other

- [gmap-server](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-server): [gmap] Remove the time-plugin requirement from gmap-server

## Release v0.17.4 - 2023-01-30(18:52:35 +0000)

### Other

- [gmap-server](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-server): [gmap] avoid using m4 odl files.

## Release v0.17.3 - 2023-01-25(17:37:20 +0000)

### Other

- [gmap-server](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-server): [gmap] the max nr of devices needs to be checked in gmaps_new_device instead of in _Devices_createDevice

## Release v0.17.2 - 2023-01-23(11:36:56 +0000)

### Other

- [gmap-mod-ethernet-dev](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-ethernet-dev): Support ARP IP down + start arping

## Release v0.17.1 - 2023-01-19(19:08:49 +0000)

### Other

- [libgmap-client](https://gitlab.com/prpl-foundation/components/gmap/libraries/libgmap-client): [amx][gmap] Expose mdns information in gMap

## Release v0.17.0 - 2023-01-19(14:45:17 +0000)

### New

- [gmap-mod-ethernet-dev](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-ethernet-dev): [import-dbg] Disable import-dbg by default for all amxrt plugin

### Other

- [gmap-mibs-common](https://gitlab.com/prpl-foundation/components/gmap/mibs/gmap-mibs-common): [amx][gmap] Expose mdns information in gMap
- [gmap-mod-ethernet-dev](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-ethernet-dev): Create IP in gmap device on gratuitous ARP
- [gmap-server](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-server): gMap server: getParameters, getFirstParameter RPC
- [gmap-server](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-server): gMap Server: DM RPC cleanup
- [libgmap-client](https://gitlab.com/prpl-foundation/components/gmap/libraries/libgmap-client): gMap server: getParameters, getFirstParameter RPC
- [libgmap-ext](https://gitlab.com/prpl-foundation/components/gmap/libraries/libgmap-ext): send ARP + callback on timeout/success

## Release v0.16.0 - 2023-01-11(11:39:17 +0000)

### New

- [libgmap-ext](https://gitlab.com/prpl-foundation/components/gmap/libraries/libgmap-ext): Component added

## Release v0.15.2 - 2023-01-10(13:35:53 +0000)

### Fixes

- [gmap-mod-self](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-self): Use search path in requires statement for instance object

### Other

- [gmap-server](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-server): GMap Server: implementation of gmap additional expression operators

## Release v0.15.1 - 2023-01-06(13:23:10 +0000)

### Fixes

- [gmap-server](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-server): Fix optional include of components.config.m4 in config/gmap_conf_global.odl.m4

## Release v0.15.0 - 2023-01-05(16:26:47 +0000)

### New

- [gmap-client](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-client): [import-dbg] Disable import-dbg by default for all amxrt plugin
- [gmap-mod-self](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-self): [import-dbg] Disable import-dbg by default for all amxrt plugin
- [libgmap-client](https://gitlab.com/prpl-foundation/components/gmap/libraries/libgmap-client): [import-dbg] Disable import-dbg by default for all amxrt plugin

### Other

- [gmap-mibs-common](https://gitlab.com/prpl-foundation/components/gmap/mibs/gmap-mibs-common): [amx][gmap] Expose mdns information in gMap
- [libgmap-client](https://gitlab.com/prpl-foundation/components/gmap/libraries/libgmap-client): [amx][gmap] gmap_devices_findByIp function uses incorrect search paths

## Release v0.14.4 - 2022-12-20(18:44:19 +0000)

### Other

- [gmap-server](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-server): Use optional include when including components.config.m4

## Release v0.14.3 - 2022-12-16(10:57:40 +0000)

### Other

- [libgmap-client](https://gitlab.com/prpl-foundation/components/gmap/libraries/libgmap-client): [amx][gmap] Expose mdns information in gMap

## Release v0.14.2 - 2022-12-08(17:06:51 +0000)

### Other

- [gmap-server](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-server): gMap Event handling
- [libgmap-client](https://gitlab.com/prpl-foundation/components/gmap/libraries/libgmap-client): gMap Event handling

## Release v0.14.1 - 2022-12-02(11:52:25 +0000)

### Other

- [gmap-mibs-common](https://gitlab.com/prpl-foundation/components/gmap/mibs/gmap-mibs-common): [amx][gmap] mib-ip fails to load due to undefined symbol
- [gmap-mod-self](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-self): Sync bridge IP from netmodel + add 'bridge' tag
- [gmap-server](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-server): [amx][gmap] mib-ip fails to load due to undefined symbol
- [libgmap-client](https://gitlab.com/prpl-foundation/components/gmap/libraries/libgmap-client): [amx][gmap] mib-ip fails to load due to undefined symbol
- [libgmap-client](https://gitlab.com/prpl-foundation/components/gmap/libraries/libgmap-client): Add IP query support

## Release v0.14.0 - 2022-11-30(08:00:55 +0000)

### New

- [gmap-mibs-common](https://gitlab.com/prpl-foundation/components/gmap/mibs/gmap-mibs-common): [gMap][wanBlock] Development of a gMap wanblock module

### Other

- [gmap-mod-ethernet-dev](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-ethernet-dev): Rename name source 'HostName'->'dhcp'
- [gmap-server](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-server): Add 'dhcp' to default name source list

## Release v0.13.11 - 2022-11-28(17:46:30 +0000)

### Other

- [gmap-mibs-common](https://gitlab.com/prpl-foundation/components/gmap/mibs/gmap-mibs-common): Add DHCPv4Client & DHCPv6Client in dhcp mib .odl

## Release v0.13.10 - 2022-11-24(11:35:59 +0000)

### Other

- [gmap-mod-ethernet-dev](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-ethernet-dev): Add DHCP option 12 HostName
- [gmap-server](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-server): gMap Server: fix gmaps_device_get_recursive

## Release v0.13.9 - 2022-11-22(07:54:07 +0000)

### Other

- [libgmap-client](https://gitlab.com/prpl-foundation/components/gmap/libraries/libgmap-client): Add gmap_ip_device_get_addresses()

## Release v0.13.8 - 2022-11-09(10:03:53 +0000)

### Other

- [gmap-mod-ethernet-dev](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-ethernet-dev): Talk to standard TR-181 DHCPv4 datamodel instead of custom notifications
- [libgmap-client](https://gitlab.com/prpl-foundation/components/gmap/libraries/libgmap-client): Add gmap_devices_findByIp

## Release v0.13.7 - 2022-10-24(13:32:19 +0000)

### Other

- [gmap-server](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-server): [gmap] Automatic clean up of inactive devices when MaxDevices is reached.
- [gmap-server](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-server): [gmap] Automatic clean up of inactive devices when MaxDevices is reached.

## Release v0.13.6 - 2022-10-13(11:22:21 +0000)

### Other

- [gmap-server](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-server): [amx][gmap] Define Name, setName(), delName() behaviour

## Release v0.13.5 - 2022-10-06(17:08:01 +0000)

### Other

- [libgmap-client](https://gitlab.com/prpl-foundation/components/gmap/libraries/libgmap-client): [amx][gmap] Define Name, setName(), delName() behaviour

## Release v0.13.4 - 2022-09-28(06:14:07 +0000)

### Other

- [gmap-mod-ethernet-dev](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-ethernet-dev): Fix fail to subscribe to DHCPv4 at boot

## Release v0.13.3 - 2022-09-26(15:28:34 +0000)

### Other

- [gmap-mod-ethernet-dev](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-ethernet-dev): fix dhcp: no IP addresses created on new lease
- [libgmap-client](https://gitlab.com/prpl-foundation/components/gmap/libraries/libgmap-client): Create unit tests for amx gMap Query feature
- [libgmap-client](https://gitlab.com/prpl-foundation/components/gmap/libraries/libgmap-client): Do not spam log on ip not found

## Release v0.13.2 - 2022-09-23(12:44:16 +0000)

### Other

- [gmap-mod-ethernet-dev](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-ethernet-dev): Various cleanup

## Release v0.13.1 - 2022-09-20(12:43:47 +0000)

### Other

- [gmap-server](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-server): [prpl][gMap]RPC topology missing
- [gmap-server](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-server): Create unit tests for amx gMap Query feature
- [gmap-server](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-server): the Devices.link() function only allows one lower device

## Release v0.13.0 - 2022-09-19(16:28:08 +0000)

### Other

- [gmap-client](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-client): Fix `/etc/init.d/gmap-client stop` not working
- [gmap-mod-ethernet-dev](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-ethernet-dev): replace using netlink with using NetDev + test

## Release v0.12.0 - 2022-09-06(07:35:42 +0000)

### New

- [gmap-server](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-server): [prpl][gMap]RPC topology missing

## Release v0.11.0 - 2022-09-02(07:26:08 +0000)

### New

- [libgmap-client](https://gitlab.com/prpl-foundation/components/gmap/libraries/libgmap-client): [prpl][gMap]RPC topology missing

## Release v0.10.6 - 2022-08-30(14:01:45 +0000)

### Other

- [gmap-client](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-client): Gmap: Fix default and make gmap default startup priority configurable
- [gmap-mod-ethernet-dev](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-ethernet-dev): Add missing requires
- [gmap-mod-name-selector](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-name-selector): Add missing requires
- [gmap-mod-self](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-self): Add missing requires
- [gmap-server](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-server): Gmap: Fix default and make gmap default startup priority configurable
- [gmap-server](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-server): Gmap: Fix default and make gmap default startup priorityr configurable

## Release v0.10.5 - 2022-08-22(15:48:10 +0000)

### Other

- [gmap-mod-self](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-self): remove "wifirepeater" tag until clear why needed

## Release v0.10.4 - 2022-08-09(10:47:53 +0000)

### Other

- [gmap-mod-ethernet-dev](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-ethernet-dev): Link dev<->port dynamically when all info is available

## Release v0.10.3 - 2022-08-08(16:23:26 +0000)

### Other

- [gmap-server](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-server): Implement using UUIDs for device keys
- [gmap-server](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-server): [prpl][gMap] gMap queries must be evaluated in the gMap server(not the lib)
- [gmap-server](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-server): [CI] Fix missing dependencies on uuid
- [libgmap-client](https://gitlab.com/prpl-foundation/components/gmap/libraries/libgmap-client): [prpl][gMap] gMap queries must be evaluated in the gMap server(not the lib)

## Release v0.10.2 - 2022-08-04(09:20:50 +0000)

### Other

- [gmap-mod-ethernet-dev](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-ethernet-dev): LAN Device must have a uuid as unique (instance)key
- [libgmap-client](https://gitlab.com/prpl-foundation/components/gmap/libraries/libgmap-client): LAN Device must have a uuid as unique (instance)key

## Release v0.10.1 - 2022-07-29(09:23:27 +0000)

### Other

- [gmap-server](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-server): test mib loading + move testhelper functions to correct test file

## Release v0.10.0 - 2022-07-27(09:40:31 +0000)

### New

- [gmap-client](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-client): Component added

### Other

- [gmap-mod-ethernet-dev](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-ethernet-dev): [Gitlab CI][Unit tests][valgrind] Pipeline doesn't stop when memory leaks are detected
- [gmap-mod-ethernet-dev](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-ethernet-dev): [prpl][gMap] gMap needs to be split in a gMap-core and gMap-client process
- [gmap-mod-name-selector](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-name-selector): [prpl][gMap] gMap needs to be split in a gMap-core and gMap-client process
- [gmap-mod-self](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-self): [prpl][gMap] gMap needs to be split in a gMap-core and gMap-client process
- [gmap-server](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-server): [prpl][gMap] gMap needs to be split in a gMap-core and gMap-client process

## Release v0.9.2 - 2022-07-14(12:54:08 +0000)

### Other

- [gmap-mod-ethernet-dev](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-ethernet-dev): Revert "common: add workaround method for retrieving intf from ifindex"
- [gmap-mod-self](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-self): Switch to using netmodel and amxs
- [libgmap-client](https://gitlab.com/prpl-foundation/components/gmap/libraries/libgmap-client): Fix `gmap_devices_unlink` doing nothing

## Release v0.9.1 - 2022-06-01(13:06:16 +0000)

### Fixes

- [gmap-mod-name-selector](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-name-selector): [Gitlab CI][Unit tests][valgrind] Pipeline doesn't stop when memory leaks are detected
- [gmap-mod-self](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-self): [Gitlab CI][Unit tests][valgrind] Pipeline doesn't stop when memory leaks are detected
- [gmap-server](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-server): [Gitlab CI][Unit tests][valgrind] Pipeline doesn't stop when memory leaks are detected

### Other

- [gmap-mod-ethernet-dev](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-ethernet-dev): Fix DHCP option 60 (vendor class) not coming through
- [libgmap-client](https://gitlab.com/prpl-foundation/components/gmap/libraries/libgmap-client): [Gitlab CI][Unit tests][valgrind] Pipeline doesn't stop when...

## Release v0.9.0 - 2022-01-28(19:52:18 +0000)

### New

- [libgmap-client](https://gitlab.com/prpl-foundation/components/gmap/libraries/libgmap-client): Add query functionality
- [gmap-server](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-server): Gmap add query functionality

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

