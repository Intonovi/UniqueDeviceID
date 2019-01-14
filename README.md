UniqueDeviceIDIntonovi
==============

PhoneGap / Cordova unique device id (UUID) plugin for Android, iOS and Windows Phone 8. Remains the same after app uninstall.

## Installation

Latest stable release: ```phonegap local plugin add cordova-plugin-UniqueDeviceIDIntonovi```  
or ```cordova plugin add cordova-plugin-UniqueDeviceIDIntonovi```

Current state from git: ```phonegap local plugin add https://github.com/Intonovi/UniqueDeviceIDIntonovi.git```  
or ```cordova plugin add https://github.com/Intonovi/UniqueDeviceIDIntonovi.git```

## Installation - PhoneGap Build 

Add following to config.xml: ```<gap:plugin name="cordova-plugin-UniqueDeviceIDIntonovi" source="npm" />```

For older versions, use the following: ```<gap:plugin name="hu.dpal.phonegap.plugins.UniqueDeviceIDIntonovi" version="1.2.0" />```
or ```<gap:plugin name="hu.dpal.phonegap.plugins.UniqueDeviceIDIntonovi" source="plugins.cordova.io" />```

## Supported Platforms

- Android
- iOS
- Windows Phone 8

## Usage

    // Get UUID
    window.plugins.UniqueDeviceIDIntonovi.get(success, fail);

Success callback function:

    function success(uuid)
    {
        console.log(uuid);
    };
