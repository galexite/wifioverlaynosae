# WifiOverlayNoSAE

Having trouble with your older Android phone or tablet trying to connect to a dual WPA2/WPA3 Personal network?

This overlay prevents your device from connecting using WPA3 SAE.

Prebuilt APKs are found in the [Releases](https://github.com/galexite/wifioverlaynosae/releases) tab.

To install, run:
```sh
adb push WifiOverlayNoSAE.apk /system/product/overlay
```

Extracted from [android_device_samsung_exynos9820-common](https://github.com/LineageOS/android_device_samsung_exynos9820-common).
