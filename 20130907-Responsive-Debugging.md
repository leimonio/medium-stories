
#Responsive Debugging

##Web development on mobile never was that easy

![http://madebyvadim.com/](https://medium2.global.ssl.fastly.net/max/2800/0*iG83GUxfEJghfWxQ.jpeg)*http://madebyvadim.com/*

#Responsive Debugging

###Web development on mobile never was that easy

Google Chrome offers **Developer Tools**, having that way access into the internal of the browser.

Ever wanted having such tools that will help your **development process on mobile**? Chrome does it in a very efficient way.

Through its tool it allows you to inspect, debug, and analyze the on-device experience with the full suite of tools you’re used to, meaning you can use the Chrome DevTools on your development machine to debug a page on your mobile device.

How to debug your web content and applications on mobile?

What you will need are:

1. An Android device with Chrome.

1. A USB cable to plug the device to your development machine.

1. The [Android SDK](http://developer.android.com/sdk/index.html) or [ADB Chrome plugin](https://chrome.google.com/webstore/detail/adb/dpngiggdglpdnjdoaefidgiigpemgage) installed on your development machine.

For the installation process follow the next steps:

1. Make sure you have installed the Android SDK or the ADB chrome plugin.

1. Enable usb debugging on your device. Settings > Developer Options > USB debugging.
(In the latter version of Android developers options are hidden by default. To enable them go to Settings > About Phone and tap Build number 7 times.)

1. Connect your device via USB to the development machine.
On your mobile device, launch Chrome and enable the USB debugging settings, going to Settings > Advanced > DevTools > Enable USB Web debugging.

1. Now you can start debugging with your ADB Chrome extension. Start ADB and then View Inspect Targets list will contain your device’s open addresses.

![](https://medium2.global.ssl.fastly.net/max/2000/0*rZtsQ26Zx0piuuid.png)**

You can now inspect and follow the development process as on your development machine. Inspect the address you want to debug and you are ready. A new window with the Chrome DevTools will appear, while your mobile browser’s document elements will be highlighted.

![](https://medium2.global.ssl.fastly.net/max/2000/0*Rr9a_YzEM3DFJ2br.png)**
