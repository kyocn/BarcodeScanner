# cordova-plugin-barcode 二维码扫描Cordova插件

This plugin implements barcode scanner on Cordova 4.0

## Supported Cordova Platforms

* Android 4.0.0 or above
* iOS 7.0.0 or above

## Use Tips
Just Use The Following Command Line word, Then You Can Call It.

cordova plugin add [插件本地路径]

## JS 
``` js
com.jieweifu.plugins.barcode.startScan(function(success){
    alert(JSON.stringify(success));
}, function(error){
    alert(JSON.stringify(error));
});
```
