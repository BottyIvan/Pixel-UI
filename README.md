# Pixel-UI

The Overlay pixel theme ported to all Andorid 8.0.

Example image:<br> <img width="50%" src="https://github.com/BottyIvan/Pixel-UI/blob/master/device-2017-08-29-160202.png?raw=true">

# You have to install <a href="https://github.com/BottyIvan/Pixel-UI/blob/master/PixelThemeOverlay.apk?raw=true">PixelThemeOverlay.apk</a> and <a href="https://github.com/BottyIvan/Pixel-UI/raw/master/app/PixelNavBar.apk">PixelNavBar.apk</a>

PixelThemeOverlay = com.google.android.theme.pixel<br>
PixelNavBar = com.botty.android.theme.pixel

Now you have to run the following commands for both apks:

<pre>$ adb shell
$ cmd overlay list
$ cmd overlay enable "PACKAGE NAME"
</pre>

# To disable them just run:

<pre>$ adb shell
$ cmd overlay list
$ cmd overlay disable "PACKAGE NAME"
</pre>

# NOTE 1
If you install two or more theme for theming the Android UI ( it's called framework-res.apk ), like the PixelThemeOverlay, you have to choose it from the list in the settings app.

<img width="50%" src="https://github.com/BottyIvan/Pixel-UI/blob/master/device-2017-08-29-160225.png?raw=true">

Like this..

# NOTE 2
If you will notice i've decompiled the PixelThemeOverlay for trying to make on my own. But for now it will crash the systemui so it will send your dvice in bootloop.<br>SO DO NOT COMPILE AND ENABLE THE PIXEL UI MODULE.
