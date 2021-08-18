# Feed_gmap

SoftAtHome feed of Openwrt packages for gMap components.

## Included components

Feed_gmap includes the following components:

### Applications

- [gmap-mod-ethernet-dev](https://gitlab.com/soft.at.home/gmap/applications/gmap-mod-ethernet-dev) - gMap component that adds discovered devices to the gmap datamodel and links them to the correct interface
- [gmap-mod-name-selector](https://gitlab.com/soft.at.home/gmap/applications/gmap-mod-name-selector) - Name selection module for gmap
- [gmap-mod-self](https://gitlab.com/soft.at.home/gmap/applications/gmap-mod-self) - gmap module to fetch information about the hgw itself and the layer 2 'devices' on it
- [gmap-server](https://gitlab.com/soft.at.home/gmap/applications/gmap-server) - Service implementing the gmap data model

### Configurations

- [gmap-mibs-common](https://gitlab.com/soft.at.home/gmap/mibs/gmap-mibs-common) - Generic mib files for the gmap service

### Libraries

- [libgmap-client](https://gitlab.com/soft.at.home/gmap/libraries/libgmap-client) - Client library for gmap modules

## How to add feed_gmap to your OpenWrt build

At the root of your OpenWrt tree, add the following to your `feeds.conf` file:

```sh
src-git feed_gmap git@gitlab.com:soft.at.home/buildsystems/openwrt/feed_gmap.git;main
```

Add the packages to your OpenWrt instance with the following commands:
```sh
./scripts/feeds update feed_gmap #retrieve the feed from service/update to latest
./scripts/feeds install -p feed_gmap #make all of the feed packages available to the build
```
