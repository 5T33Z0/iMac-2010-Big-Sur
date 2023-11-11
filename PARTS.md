# `iMac11,3` Upgrades
List of possible/suitabe hardware upgrades running macOS 12 and newer

## CPU Upgrage Options

Lynfield Desktop or Server CPUs:

- Intel Core [i7-870](https://ark.intel.com/content/www/de/de/ark/products/48500/intel-core-i7880-processor-8m-cache-3-06-ghz.html) (officially supported by SMBIOS) / [i7-880](https://ark.intel.com/content/www/de/de/ark/products/48500/intel-core-i7880-processor-8m-cache-3-06-ghz.html)
- Intel Xeon [X3470](https://ark.intel.com/content/www/de/de/ark/products/42932/intel-xeon-processor-x3470-8m-cache-2-93-ghz.html) / [X3480](https://ark.intel.com/content/www/de/de/ark/products/48501/intel-xeon-processor-x3480-8m-cache-3-06-ghz.html). Cheaper, supports up to 32 GB RAM (including ECC).

> [!NOTE]
> 
> Unfortunately, none of the 1st Gen Intel Core/Xeon CPUs are supported by ssdtPRGen or Intel Power Gadget, so monitoring as well as adjusting CPU Power Management is not possible, afaik.

## GPU Options
Although you can install and run macOS Sonoma on this iMac, a GPU upgrade is required if you need Metal support. I haven't yet decided if I want to invest in a GPU upgrade for this iMac since I have a powerful Workstation with an i9-10850K CPU.

In my tests of macOS 14.1, the grid, locators and playhead were missing from Logic Pro 10.8 since it uses Metal to render them. 

Listed below, you find some links regarding GPU upgrade:

- [**GPU Upgrade Guide**](https://forums.macrumors.com/threads/2011-imac-graphics-card-upgrade.1596614/) on Macrumors.
- [**iMac 2009 to 2011 Upgrade Guide**](http://macintoshmen.is-great.net/2019/09/08/imac-2009-to-2011-upgrade-guide/?i=1) by macintoshmen. Has a lot of helpful videos.
- **Other**: [Dell Precision 7710 7720 AMD FirePRO WX7100 8GB GDDR5](https://de.aliexpress.com/item/1005001997429932.html?gatewayAdapt=glo2deu)
- [**AMD VBIOS Collection**](https://github.com/Ausdauersportler/IMAC-EFI-BOOT-SCREEN)

> [!NOTE]
> 
>  GPU upgrades require flashing the correct vBIOS and some even require a different heatsink.


## USB3, WIFI and Bluetooth

- [**USB3 and Wi-Fi Upgrade Guide**](https://forums.macrumors.com/threads/usb-3-wifi-ac-bt4-2-for-imac-27-mid-2010.2269396)
- **WiFi/BT Card**: Ebay [**search reults**](https://www.ebay.co.uk/sch/i.html?_nkw=Apple+MacBook+Air+11%E2%80%9D+A1465+13%E2%80%9D+A1466+Airport+Bluetooth+Wifi+Card+Z653-0020%2B) 


## SSD Mount (3D print)
- https://www.thingiverse.com/thing:2267285
