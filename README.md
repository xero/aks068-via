# AKS068 keyboard VIA config files

this board is sold under a few names: a-jazz, attack shark, mambasnake... and comes in two flavors. wired and trimode with additional bluetooth and 2.4g wireless.

this repo contains __working__ VIA json programming files for both the [wired](https://amzn.to/3WEuj2R) and [pro](https://amzn.to/3WqCIpa) versions of the AKS068 keyboard. plus my custom layout.

here's my current layout:

![layer 0](keeb-layer0.png)
![layer 1](keeb-layer1.png)

using the [via web app](http://usevia.app) (here's a great [tutorial](https://epomaker.com/blogs/guides/how-to-use-via-for-beginners)), under settings: enable the `design` option. since this keeb uses a hacky implementation of the standard, ensure you enabled the `Use V2 definitions (deprecated)` option when loading the via.json files. there's a discrete config for both wired/bluetooth and 2.4g modes for some reason. both the standard wired and pro use the [via-usb.json](AKS068-via-usb.json) file. the other files only applies to the pro version. once the config is loaded you can import my [custom layout](AKS068-layout.json) or use the designer to create your own.
