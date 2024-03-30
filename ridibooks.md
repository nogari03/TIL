우분투 22.04에서 Ridibooks viewer 설치(android)

```console
$ sudo apt install curl ca-certificates

$ curl https://repo.waydro.id | sudo bash

$ sudo apt install waydroid

$ sudo waydroid init

# https://ridi.github.io/RIDI-Android-APK/
$ waydroid app install RIDI-24.3.1-PlayStore.apk

$ waydroid app list
$ waydroid app launch com.initialcoms.ridi

# /var/lib/waydroid/waydroid.cfg

$ waydroid prop set persist.waydroid.height ""
$ waydroid prop set persist.waydroid.width 506

$ systemctl restart waydroid-container
```

ref :
https://medium.com/@jasonlife/run-ridi-android-app-on-ubuntu-22-04-with-waydroid-59700cacacdc