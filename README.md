# Lenovo-X50-macOS
#### This repository contains scripts and ACPI patches for some Lenovo (Haswell) series to get macOS Catalina installed and running.

It uses (and depends on) scripts & tools already existing in https://github.com/AD2076/macos-tools and forked from https://github.com/the-braveknight/macos-tools.
It also fetches some of RehabMan's latest hotpatch SSDTs from https://github.com/RehabMan/OS-X-Clover-Laptop-Config.

### Supported Models
- Lenovo Z50-70/Z40-70 (use make install_z50)
- Lenovo G50-70/G40-70 (use make install_g50)

### Changelog
2019-12-03
- Always use CLOVER/kexts/Other
- Add Catalina 10.15 support

2018-09-30
- Drop ELAN kext support due to author's disregard to APSL
- Add Mojave 10.14 support

2017-12-16
- Added support for G50-70 series
- Added a makefile
