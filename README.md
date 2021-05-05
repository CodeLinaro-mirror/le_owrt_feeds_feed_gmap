# OpenWrt/LEDE packages for gmap components
Soft At Home Feed of Openwrt/LEDE packages for gmap components

## How to add the gmap Feed to you OpenWrt/LEDE build
At the root of your OpenWrt/LEDE tree, add the following to your `feeds.conf` file:
```sh
src-git feed_gmap https://gitlab.com/soft.at.home/buildsystems/openwrt/feed_gmap.git;master
```
Now to add the packages on your gmap feed to your OpenWrt/LEDE instance:
```sh
./scripts/feeds update feed_gmap #retrieve the gmap feed from service/update to latest
./scripts/feeds install -p feed_gmap #make all of the gmap feed packages available to the build
```