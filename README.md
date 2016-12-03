![Build Status](https://forcedotcom.github.io/SalesforceMobileSDK-TestResults/CordovaPlugin-results/latest/buildstatus.svg)

Steps to use the Cordova plugin for the Salesforce Mobile SDK
------------------------

<pre>
npm install cordova -g

cordova create TestApp
cd TestApp
cordova plugin add https://github.com/forcedotcom/SalesforceMobileSDK-CordovaPlugin
cordova platform add android@6.1.0
cordova platform add ios@4.3.0
cordova prepare
</pre>

For more information, check out [Salesforce Mobile SDK Development Guide](https://github.com/forcedotcom/SalesforceMobileSDK-Shared/blob/master/doc/mobile_sdk.pdf?raw=true)
