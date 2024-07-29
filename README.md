# AKS068 keyboard VIA programming files

the AKS068 is an ergonomic alice/arisu style keyboard sold under a few names: ajazz, attack shark, mambasnake... it comes in two flavors: wired and pro, which is tri-mode wired, bluetooth, and 2.4g wireless.

this repo contains __working__ VIA json programming files for both the [wired](https://amzn.to/3WEuj2R) and [pro](https://amzn.to/3WqCIpa) versions of the AKS068 keyboard. _unlike what's on their website._ plus my custom layout.

## preview

here's my personal layout:

![keyboard layout](https://raw.githubusercontent.com/xero/aks068-via/main/layout-preview.png)

## how to

using the [via web app](http://usevia.app) (here's a great [tutorial](https://epomaker.com/blogs/guides/how-to-use-via-for-beginners)), under settings: enable the `design` option. since this keeb uses a hacky implementation of the standard, ensure you enabled the `Use V2 definitions (deprecated)` option when loading the via.json files. there's a discrete config for both wired/bluetooth and 2.4g modes for some reason. both the standard wired and pro use the [via-usb.json](AKS068-via-usb.json) file. the [via-24g.json](AKS068-via-24g.json) only applies to the pro version (you will need to disconnect and reconnect modes to flash both seperately). once the config is loaded you can import my [custom layout](AKS068-layout.json) or use the designer to create and export your own.


## references

* https://epomaker.com/blogs/guides/how-to-use-via-for-beginners
* https://epomaker.com/blogs/via-json/ajazz-aks068-pro-usb-json-file
* https://epomaker.com/blogs/via-json/ajazz-aks068-pro-2-4g-json-file
* https://attackshark.com/products/attackshark-ajazz-aks068pro-ergonomic-alicelayout
* https://www.a-jazz.com/en/search.jsp?id=422&q=AKS068
* https://www.caniusevia.com/docs/specification
* https://usevia.app

## license

![kopimi logo](https://gist.githubusercontent.com/xero/cbcd5c38b695004c848b73e5c1c0c779/raw/6b32899b0af238b17383d7a878a69a076139e72d/kopimi-sm.png)

all files and scripts in this repo are released [CC0](https://creativecommons.org/publicdomain/zero/1.0/) / [kopimi](https://kopimi.com)! in the spirit of _freedom of information_, i encourage you to fork, modify, change, share, or do whatever you like with this project! `^c^v`
