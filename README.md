# Super Simple Chat Demo, using PubNub Cordova Plugin

This demo utilizes Pubnub's Phonegap Plugin, available from: https://build.phonegap.com/plugins/2382, also available via the Cordova plugins directory at: http://plugins.cordova.io/#/package/com.pubnub.cordova.pubnub

![image](http://www.pubnub.com/blog/wp-content/uploads/2014/10/phonegap.jpg)

## How to Run this Demo App

You can *either* use [PhoneGap Build](https://build.phonegap.com/apps) cloud tool, or build it by yourself using Cordova command-line interface (CLI) tools.

### 1. Using PhoneGap Build

1. Go to [PhoneGap Build](https://build.phonegap.com/apps) and sign in
2. Click **"+ New App"** button
3. Paste this Git URL, *https://github.com/pubnub/cordova-plugin-demo.git* in the field (the branch is *master* but you can leave it blank)
4. Click the **"Pull from .git repository"** button
5. When it finish fetching the code, click **Ready to Build**
6. Scan the QR Code with your device, and install

or,

### 2. Using Cordova CLI

Clone this repo, add mobile platforms (e.g. Andorid), add plugin, then run!

1. `$ git clone https://github.com/pubnub/cordova-plugin-demo.git`
2. `$ cd cordova-plugin-demo`
3. `$ cordova platform add android` (or other mobile platforms you need) 
4. `$ cordova plugin add com.pubnub.cordova.pubnub`
5. `$ cordova run`
