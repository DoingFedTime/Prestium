# Changelog

All notable changes will be kept in this file.



## [1.2.1] - 2023-01-13

### Changed

- HexChat: irc_logging directive set to 0
- HexChat: text_replay directive set to 0

### Updated

- LibreWolf to 108.0.2-1
- i2pd to 2.45.1

## [1.2.O] - 2023-01-06

### Added

- QtQR, Offline QR code generator
- StormyCloud's outproxy
- Purokishi outproxy is left commented out
- Tray battery status for laptops
- Prevent SATA controller from being loaded (ahci, libahci, libata)
- Important boot options, such as mds, init_on_free, init_on_alloc, page_poison, etc
- Realtek PCI-Express ethernet firmware (r8168)
- Intel ethernet e1000e driver
- Proprietary AMD, Intel and other miscellaneous firmware
- Support for Plug'n'Play USB WiFi dongles

### Changed

- Official OS name to Prestium
- Hostname from i2p to prestium
- i2pd: bandwidth from P to X
- i2pd: bandwidth share from 50% to 100%
- i2pd: limit inbound and outbound quantity for every tunnel to 2; Client Tunnels drop from 150 to ~50, thank you, zzz!
- Right-click menu entries, resorted and added QtQr
- LibreWolf now uses only HTTP(s) proxy

### Updated

- Debian packages, security patches
- LibreWolf web browser
- i2pd from 2.43.0 to 2.45.0
- Linux kernel from 5.10.0-18 to 5.10.0-20

### Fixed

- Frequent HexChat (IRC) disconnects: Increased HexChat's net_ping_timeout directive from 60 to 600; thank you, undisclosed IRC user!
- Need for force shutdown on login

### Removed

- 32bit support, only amd64 (64bit) is now officially supported
- Password for "user" account, now you only need to type "user" when logging in
- Old kernel and old kernel modules
- SOCKS5 proxy from LibreWolf's "pref" config
- SOCKS5 proxy for LibreWolf

## [1.1.0] - 2022-11-10

### Added

- This changelog file
- WiFi support for the following chipsets: Intel, Broadcom, Realtek and Atheros
- Network Manager
- VeraCrypt
- Cryptsetup (LUKS)
- VLC Media player
- MacChanger, enabled by default
- Prevent loading Bluetooth kernel modules

### Fixed

- File naming

## [1.0.0] - 2022-11-09
