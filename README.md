DPO_MT7601U_LinuxSTA
====================

MT7601U Driver +Xiaodu WiFi +360 WiFi Gen 2

Kernel Configuration
--------------------
+    select WIRELESS_EXT
+    select WEXT_PRIV

Firmware
--------------------
Download mt7691u.bin from here

http://git.kernel.org/cgit/linux/kernel/git/firmware/linux-firmware.git/plain/mt7601u.bin

RT2870STA.dat
--------------------
```
mkdir -p /etc/Wireless/RT2870STA/
cp RT2870STA.dat /etc/Wireless/RT2870STA/RT2870STA.dat
```

