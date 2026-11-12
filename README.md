# RF Scanner updates

Firmware releases for the RF Scanner, a 2.4 GHz scanner that helps choose a
clear Profoto Air channel on set.

There is nothing to download by hand. To update a scanner:

1. Join the scanner's Wi-Fi network (`RF-Scanner-xxxx`).
2. Open the Update page (`http://192.168.4.1/update`).
3. The first time, save a Wi-Fi network that has internet. A phone hotspot works.
4. Tap **Check for updates**.

The scanner joins that network for up to a minute, installs the latest
release from this repository if it is newer than what it has, and restarts.

Each release contains two files:

- `RFScanner.bin`: the firmware
- `version.txt`: its version number
