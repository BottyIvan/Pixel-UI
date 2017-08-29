# Pixel-UI

The Overlay pixel theme ported to all Andorid 8.0.

So here is how will look <img width="50%" src="https://github.com/BottyIvan/Pixel-UI/blob/master/device-2017-08-29-160202.png?raw=true">

#You need to install <a href="">PixelThemeOverlay.apk</a> and <a href="">PixelNavBar.apk</a>

PixelThemeOverlay = com.google.android.theme.pixel
PixelNavBar = com.botty.android.theme.pixel

Now you need to run thi few command for both apks:

<pre>$ adb shell
$ cmd overlay list
$ cmd overlay enable "NAME PACKAGE"
</pre>

#Do disable this two theme:

<pre>$ adb shell
$ cmd overlay list
$ cmd overlay disable "NAME PACKAGE"
</pre>

#NOTE 1
If you install two or more theme for theming the all Android UI ( it's called framework-res.apk ), like the PixelThemeOverlay, you will eanble the option to choose theme in the settings app.

<img width="50%" src="https://github.com/BottyIvan/Pixel-UI/blob/master/device-2017-08-29-160225.png?raw=true">

Like this..

#NOTE 2
If you will notice i've decompiled the PixelThemeOverlay for trying to make on my own. But for now it will crash the systemui so it will send your dvice in bootloop.<br>SO DO NOT COMPILE AND ENABLE THE PIXEL UI MODUEL.
