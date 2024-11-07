SNTP example
============

This example shows using the SNTP library to fetch the time and then prints the UNIX time every second.
Try extending this to use two threads and update the time via SNTP periodically to account for clock drift.

## Building on Sonata

```sh
rm -rf build .xmake
xmake config --sdk=/path/to/cheriot-llvm --board=sonata-prerelease --IPv6=false
xmake
```
