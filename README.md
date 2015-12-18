Air Native Extension for Google Play Games Services (Android)
======================================

This is an [Air native extension](http://www.adobe.com/devnet/air/native-extensions-for-air.html) for [Google Play Games Services](http://developer.android.com/google/play-services/games.html/) SDK on Android. It has been developed by [FreshPlanet](http://freshplanet.com) and is used in the game [MoviePop](http://moviepop.net).


Installation
---------

The ANE binary (AirGooglePlayServices.ane) is located in the *bin* folder. You should add it to your application project's Build Path and make sure to package it with your app (more information [here](http://help.adobe.com/en_US/air/build/WS597e5dadb9cc1e0253f7d2fc1311b491071-8000.html)).


Usage
-----

google-play-services.jar and android-support-v4.jar for ANE libs

Use this with my versions of AirPushNotification or AirGooglePlayGameServices.ane, for in app purchase you can use [StarIslandGames's](https://github.com/StarIslandGames/ANE-In-App-Purchase) version

If you use [lilili87222’s AdMob](https://github.com/lilili87222/admob-for-flash) use the without_gps version


Build script
---------

Should you need to edit the extension source code and/or recompile it, you will find an ant build script (build.xml) in the *build* folder:

```bash
cd /path/to/the/ane/build
mv example.build.config build.config
#edit the build.config file to provide your machine-specific paths
ant
```
