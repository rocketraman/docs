# Using ADB with Waydroid

Ensure that `/var/lib/waydroid/waydroid.cfg` contains `auto_adb = True` in the `[waydroid]` section.

Grab the waydroid IP address from **Android Settings-> About**

And use it to connect via adb:

```
adb connect <IP>:5555
```
