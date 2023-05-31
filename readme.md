readme.md

```
cd ~ && esptool.py --port /dev/ttyS0 erase_flash && esptool.py --port /dev/ttyS0 write_flash 0x0 ./WLED_0.13.0-b3_ESP8266.bin
```
![Flashing](flashing.jpg)
