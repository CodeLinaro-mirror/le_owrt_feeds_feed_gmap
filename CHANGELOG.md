# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]


## Release proj_prpl_M4-2022_v0.1.0 - 2022-12-19(15:14:34 +0000)

### New

- [gmap-client](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-client): Component added
- [gmap-mibs-common](https://gitlab.com/prpl-foundation/components/gmap/mibs/gmap-mibs-common): [gMap][wanBlock] Development of a gMap wanblock module
- [gmap-server](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-server): [prpl][gMap]RPC topology missing
- [libgmap-client](https://gitlab.com/prpl-foundation/components/gmap/libraries/libgmap-client): [prpl][gMap]RPC topology missing

### Fixes

- [gmap-mod-name-selector](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-name-selector): [Gitlab CI][Unit tests][valgrind] Pipeline doesn't stop when memory leaks are detected
- [gmap-mod-self](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-self): [Gitlab CI][Unit tests][valgrind] Pipeline doesn't stop when memory leaks are detected
- [gmap-server](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-server): [Gitlab CI][Unit tests][valgrind] Pipeline doesn't stop when memory leaks are detected

### Other

- [gmap-mibs-common](https://gitlab.com/prpl-foundation/components/gmap/mibs/gmap-mibs-common): [amx][gmap] mib-ip fails to load due to undefined symbol
- [gmap-mibs-common](https://gitlab.com/prpl-foundation/components/gmap/mibs/gmap-mibs-common): Add DHCPv4Client & DHCPv6Client in dhcp mib .odl
- [gmap-mod-ethernet-dev](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-ethernet-dev): [Gitlab CI][Unit tests][valgrind] Pipeline doesn't stop when memory leaks are detected
- [gmap-mod-ethernet-dev](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-ethernet-dev): Fix DHCP option 60 (vendor class) not coming through
- [gmap-mod-ethernet-dev](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-ethernet-dev): Revert "common: add workaround method for retrieving intf from ifindex"
- [gmap-mod-ethernet-dev](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-ethernet-dev): LAN Device must have a uuid as unique (instance)key
- [gmap-mod-ethernet-dev](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-ethernet-dev): [prpl][gMap] gMap needs to be split in a gMap-core and gMap-client process
- [gmap-mod-ethernet-dev](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-ethernet-dev): Link dev<->port dynamically when all info is available
- [gmap-mod-ethernet-dev](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-ethernet-dev): replace using netlink with using NetDev + test
- [gmap-mod-ethernet-dev](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-ethernet-dev): Various cleanup
- [gmap-mod-ethernet-dev](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-ethernet-dev): Add missing requires
- [gmap-mod-ethernet-dev](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-ethernet-dev): fix dhcp: no IP addresses created on new lease
- [gmap-mod-ethernet-dev](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-ethernet-dev): Fix fail to subscribe to DHCPv4 at boot
- [gmap-mod-ethernet-dev](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-ethernet-dev): Talk to standard TR-181 DHCPv4 datamodel instead of custom notifications
- [gmap-mod-ethernet-dev](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-ethernet-dev): Add DHCP option 12 HostName
- [gmap-mod-ethernet-dev](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-ethernet-dev): Rename name source 'HostName'->'dhcp'
- [gmap-mod-name-selector](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-name-selector): [prpl][gMap] gMap needs to be split in a gMap-core and gMap-client process
- [gmap-mod-name-selector](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-name-selector): Add missing requires
- [gmap-mod-self](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-self): Switch to using netmodel and amxs
- [gmap-mod-self](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-self): [prpl][gMap] gMap needs to be split in a gMap-core and gMap-client process
- [gmap-mod-self](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-self): remove "wifirepeater" tag until clear why needed
- [gmap-mod-self](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-self): Add missing requires
- [gmap-mod-self](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-mod-self): Sync bridge IP from netmodel + add 'bridge' tag
- [gmap-server](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-server): Implement using UUIDs for device keys
- [gmap-server](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-server): test mib loading + move testhelper functions to correct test file
- [gmap-server](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-server): [prpl][gMap] gMap needs to be split in a gMap-core and gMap-client process
- [gmap-server](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-server): [prpl][gMap] gMap queries must be evaluated in the gMap server(not the lib)
- [gmap-server](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-server): [prpl][gMap]RPC topology missing
- [gmap-server](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-server): Create unit tests for amx gMap Query feature
- [gmap-server](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-server): gMap Server: fix gmaps_device_get_recursive
- [gmap-server](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-server): Gmap: Fix default and make gmap default startup priority configurable
- [gmap-server](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-server): Gmap: Fix default and make gmap default startup priorityr configurable
- [gmap-server](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-server): the Devices.link() function only allows one lower device
- [gmap-server](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-server): [amx][gmap] Define Name, setName(), delName() behaviour
- [gmap-server](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-server): [gmap] Automatic clean up of inactive devices when MaxDevices is reached.
- [gmap-server](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-server): [gmap] Automatic clean up of inactive devices when MaxDevices is reached.
- [gmap-server](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-server): gMap Event handling
- [gmap-server](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-server): [amx][gmap] mib-ip fails to load due to undefined symbol
- [gmap-server](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-server): Add 'dhcp' to default name source list
- [gmap-server](https://gitlab.com/prpl-foundation/components/gmap/applications/gmap-server): [CI] Fix missing dependencies on uuid
- [libgmap-client](https://gitlab.com/prpl-foundation/components/gmap/libraries/libgmap-client): [Gitlab CI][Unit tests][valgrind] Pipeline doesn't stop when...
- [libgmap-client](https://gitlab.com/prpl-foundation/components/gmap/libraries/libgmap-client): Fix `gmap_devices_unlink` doing nothing
- [libgmap-client](https://gitlab.com/prpl-foundation/components/gmap/libraries/libgmap-client): LAN Device must have a uuid as unique (instance)key
- [libgmap-client](https://gitlab.com/prpl-foundation/components/gmap/libraries/libgmap-client): [prpl][gMap] gMap queries must be evaluated in the gMap server(not the lib)
- [libgmap-client](https://gitlab.com/prpl-foundation/components/gmap/libraries/libgmap-client): Create unit tests for amx gMap Query feature
- [libgmap-client](https://gitlab.com/prpl-foundation/components/gmap/libraries/libgmap-client): [amx][gmap] Define Name, setName(), delName() behaviour
- [libgmap-client](https://gitlab.com/prpl-foundation/components/gmap/libraries/libgmap-client): Do not spam log on ip not found
- [libgmap-client](https://gitlab.com/prpl-foundation/components/gmap/libraries/libgmap-client): Add gmap_devices_findByIp
- [libgmap-client](https://gitlab.com/prpl-foundation/components/gmap/libraries/libgmap-client): gMap Event handling
- [libgmap-client](https://gitlab.com/prpl-foundation/components/gmap/libraries/libgmap-client): [amx][gmap] mib-ip fails to load due to undefined symbol
- [libgmap-client](https://gitlab.com/prpl-foundation/components/gmap/libraries/libgmap-client): Add gmap_ip_device_get_addresses()
- [libgmap-client](https://gitlab.com/prpl-foundation/components/gmap/libraries/libgmap-client): Add IP query support

## Release proj_prpl_v0.0.1 - 2022-03-28(14:58:47 +0000)

