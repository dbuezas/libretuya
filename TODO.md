# TODO list

## General

### New families

- BL602
- RTL8710A
- RTL8720C
- RTL8720D
- W600 and/or W800
- LN8825
- host-native family

### Tools

- write OpenOCD flashers, using uf2ota library + FAL for partitions (in ltchiptool repository)

### Serial

- configuration of RX/TX pins
- SoftwareSerial library - receiving + Beken family

### Other

- watchdog API
- `Preferences` library
- test/fix IPv6 on different families
- what is `PowerManagement` at all? probably useless -> remove

## BK7231

- implement OTA
- fix WiFi on BK7231N, test other functionality
- fix SSL (mbedTLS)
- I2C (Wire)
- SPI
- BLE

## RTL8710B

- move to GNU++11 (and verify that it works) - take all stdio functions from stdio.h
- rewrite most of Wiring (it was copied from `ambd_arduino`, and is ugly)
