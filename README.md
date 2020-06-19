Create new blank Ionic Project 6.10.0
add cordova
ionic cordova plugin add cordova-plugin-firebasex
ionic cordova plugin add https://github.com/mapsplugin/cordova-plugin-googlemaps#multiple_maps

PS D:\Progetti\testApp> ionic cordova build android
> cordova.cmd platform add android --save
Using cordova-fetch for cordova-android@^8.0.0
Adding android project...
Creating Cordova project for the Android platform:
        Path: platforms\android
        Package: io.ionic.starter
        Name: MyApp
        Activity: MainActivity
        Android target: android-28
Subproject Path: CordovaLib
Subproject Path: app
Android project created with cordova-android@8.1.0
Installing "cordova-plugin-firebasex" for android
Installing "cordova-plugin-androidx" for android
Installing "cordova-plugin-androidx-adapter" for android
Subproject Path: CordovaLib
Subproject Path: app
Installing "cordova-plugin-googlemaps" for android
Installing "cordova-androidx-build" for android
Subproject Path: CordovaLib
Subproject Path: app
Subproject Path: CordovaLib
Subproject Path: app

      Official document https://github.com/mapsplugin/cordova-plugin-googlemaps-doc/blob/master/v2.6.0/README.md Please consider to buy a beer for us 🍺 https://github.com/mapsplugin/cordova-plugin-googlemaps#buy-us-a-beer

--[cordova-androidx-build]------------------------
Since cordova-plugin-androidx-adapter breaks cordova-androidx-build code,
uninstall cordova-plugin-androidx-adapter automatically.
-----------------------------------------------------
Command failed: cordova plugin rm cordova-plugin-androidx-adapter 2>&1

[ERROR] An error occurred while running subprocess cordova.

        cordova.cmd platform add android --save exited with exit code 1.

        Re-running this command with the --verbose flag may provide more information.


        