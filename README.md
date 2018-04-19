# YandexPDDOpenWRT
This script will update DNS ip's when WAN interface was reconnected.


### Instruction:
* Enable SSH
* Install Curl and ca-certificate (System -> Software -> Search -> install) or:
  ```bash
  opkg update
  opkg install curl ca-certificate ca-bundle```
* Edit script and save as: `/etc/hotplug.d/iface/99-yapdd`
