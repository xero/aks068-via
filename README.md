# AKS068 keyboard VIA config files

the AKS068 is an ergonomic alice/arisu style keyboard sold under a few names: ajazz, attack shark, mambasnake... & comes in two flavors, wired & trimode w/ additional bluetooth & 2.4g wireless.

this repo contains __working__ VIA json programming files for both the [wired](https://amzn.to/3WEuj2R) & [pro](https://amzn.to/3WqCIpa) versions of the AKS068 keyboard. _unlike what's on their website._ plus my custom layout.

# preview

here's my current layout:

![layer 0](keeb-layer0.png)
![layer 1](keeb-layer1.png)

## how to

using the [via web app](http://usevia.app) (here's a great [tutorial](https://epomaker.com/blogs/guides/how-to-use-via-for-beginners)), under settings: enable the `design` option. since this keeb uses a hacky implementation of the standard, ensure you enabled the `Use V2 definitions (deprecated)` option when loading the via.json files. there's a discrete config for both wired/bluetooth & 2.4g modes for some reason. both the standard wired & pro use the [via-usb.json](AKS068-via-usb.json) file. the [via-24g.json](AKS068-via-24g.json) only applies to the pro version (you will need to disconnect & reconnect modes to flash both seperately). once the config is loaded you can import my [custom layout](AKS068-layout.json) or use the designer to create & export your own.
