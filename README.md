# Liberate your EasyBox 904 xDSL for Telekom Users
## Use it with every Provider without MIC (Modem Installation Code)

This is a step by step guide to open your easybox 904 xDSL for the usage with every provider (Telekom, 1&1 etc). This Guide is only supported for the 904 xDSL (the firmware of the 804 is protected by encryption and cannot be modified this easy, the 904 LTE could work). The Guide will also work with almost any vectoring connection.

From here on you have five options:

1. [Quick and easy](https://github.com/arasharchor/easybox904-f-r-TelekomBenutzer/blob/master/simple.md) guide, uses the original Vodafone firmware with every ISP. [Also available in german](https://github.com/arasharchor/easybox904-f-r-TelekomBenutzer/blob/master/german.md)
---

## General Tips

Get the complete config:
```
ccfg_cli showcfg
```
Read a specific configuration entry:
```
ccfg_cli get xxx
```

>*Thanks to Quallenauge for the work over at his [openWrt-fork](https://github.com/Quallenauge/Easybox-904-XDSL) and the [openWrt-forum](https://forum.openwrt.org/viewtopic.php?id=44676). Huge portions of this guide were taken from the openwrt forum. Please thank these guys for the affords! Specials thanks to all the issues and feedback I get in this repo, you guys keep me going :)*
