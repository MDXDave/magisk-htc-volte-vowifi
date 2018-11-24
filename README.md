## VoLTE/VoWIFI Enabler for HTC U11/U12+ (german providers) 

This modules enables Voice over LTE (VoLTE) and Wifi-Calling (VoWIFI) for the HTC U11/U12+ on german providers (Deutsche Telekom, Vodafone DE, o2/E-Plus). 

By default, the HTC U12+ (and partially the U11) does not ship with support for VoLTE/VoWifi for german providers. Works with the WWE/Europe-Version of the phones.

### Changes

The module adds configuration files (systemlessly) to support VoLTE/VoWifi:
- system/customize/MNS/26201.xml (DTAG)
- system/customize/MNS/26202.xml (VFDE)
- system/customize/MNS/26203.xml (E-Plus)
- system/customize/MNS/26207.xml (o2)
- system/customize/MNS/26208.xml (o2)
- system/customize/MNS/26211.xml (o2)

It overrides the following files (systemlessly):
- system/customize/mns_map.xml
- system/customize/ACC/default.xml
- system/customize/ACC/HTC__034.xml

### Changelog

v1.0 (2018-11-24)
- Initial release