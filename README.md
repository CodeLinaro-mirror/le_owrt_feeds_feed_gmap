# OpenWrt/LEDE packages for usp components
Soft At Home Feed of Openwrt/LEDE packages for usp components

## How to add the usp Feed to you OpenWrt/LEDE build
At the root of your OpenWrt/LEDE tree, add the following to your `feeds.conf` file:
```sh
src-git feed_gmap git@gitlab.com:soft.at.home/gmap/buildsystems/openwrt/feed_gmap.git
```
Now to add the packages on your usp feed to your OpenWrt/LEDE instance:
```sh
./scripts/feeds update feed_gmap #retrieve the usp feed from service/update to latest
./scripts/feeds install -p feed_gmap #make all of the usp feed packages available to the build
```
