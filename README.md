# YandexPDDOpenWRT
Update Yandex DNS records whe IP on WAN interface is changed


### Instruction:
* Install Curl and ca-certificate (System -> Software -> Search / install) or:
  ```bash
  opkg update
  opkg install curl ca-certificates ca-bundle
  ```
* Enable SSH
* Edit variables in script and save as: `/etc/hotplug.d/iface/99-yapdd`
