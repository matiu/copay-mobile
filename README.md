# Copay Mobile

The goal of this project is to create the best bitcoin wallet for mobiles by 
using the multisig power of Copay and making it context aware.


## Install

    sudo npm install -g cordova ionic gulp
    git clone https://github.com/yemel/copay-mobile.git
    cd copay-mobile
    npm install

## Cordova Plugins

    cordova plugin add org.apache.cordova.statusbar
    cordova plugin add org.apache.cordova.vibration
    cordova plugin add org.apache.cordova.splashscreen
    cordova plugin add de.appplant.cordova.plugin.local-notification
    cordova plugin add https://github.com/wildabeast/BarcodeScanner.git
    cordova plugin add https://github.com/VersoSolutions/CordovaClipboard
    cordova plugin add https://github.com/EddyVerbruggen/Toast-PhoneGap-Plugin.git
    cordova plugin add de.appplant.cordova.plugin.email-composer & cordova prepare
    cordova plugin add https://github.com/EddyVerbruggen/SocialSharing-PhoneGap-Plugin.git
    cordova plugin add https://github.com/EddyVerbruggen/LaunchMyApp-PhoneGap-Plugin.git --variable URL_SCHEME=bitcoin

## Run

Run it on the IOS emulator:

    $ ionic platform add ios
    $ ionic emulate ios

Run it on an Android device:

    $ ionic platform add android
    $ ionic run android

Test it on the web browser:

    $ ionic serve

You may check an online demo here: http://copay.herokuapp.com/
