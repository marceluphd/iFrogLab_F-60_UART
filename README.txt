
### iFrogLab F60 UART ###

===========================================================================
Device and Video Tutorials

the item could be purchased at 
http://www.ifroglab.com

more video tutorial and demo could watch at 
https://www.youtube.com/playlist?list=PLkvu6TsdkQFoXUIVTa7cfhMmow_DUehXU

source code could be download from 
https://github.com/powenko/iFrogLab_F60_UART

the iFrogLab F-60 BLE hardware available at amazon.com
https://www.amazon.com/iFrogLab-Bluetooth-Transceiver-Connect-Raspberry/dp/B01CYX30KM/ref=sr_1_1?ie=UTF8&qid=1475881031&sr=8-1&keywords=ifroglab



===========================================================================
DESCRIPTION:

iFrogLab F60 for Bluetooth Low Energy (BLE) Shield. It is designed to work with Arduino boards, Raspberry Pi or compatibles, including Arduino Uno, Mega 2560, Leonardo, Due, Raspberry Pi and Raspberry Pi 2,  It allows you to connect your Arduino/Raspberry Pi boards with other BLE Central device like a smartphone or tablet. So you can develop some applications like:

*. Control your Arduino pins with our/your own mobile App
*. Send sensor data from your Arduino to an App for processing
*. Use your mobile device as an internet gateway for your Arduino
and much more!
*. BLE shield could operate und



This iFrogLab F60 UART is a bluetooth model, you could use with an Arduino, Raspberry Pi and any electical device, the source code is 
used standalone, plugged into another Arduino or it can also be plugged into a Raspberry pi. You can run Arduino software on this shield and access the Raspberry Pi that it is plugged into. Its essential function is a Bluetooth hardware module A 4.2 (UART) BLE-Nordic nRF51822 Bluetooth 4.2 module (Single Mode). It can run standalone using the Arduino that is built in. Or you can plug it into a Raspberry Pi and this module can access everything on the Raspberry Pi. The Raspberry Pi can also access all functions on this board. An Arduino library was developed that you can plug into the Arduino Uno IDE. Using this library you can directly access all Arduino and Raspberry Pi I/O peripherals. This allows you to stack many Arduino boards to build really interesting modules that were not possible before. The Arduino can access external sensors and it supports Apple iOS / Android / Raspberry Pi for UART data transmission. This board supports the Bluetooth SIG specification 4.0 and 4.2 specifications. This is a very unique board that we developed in-house that no one else has. We will provide many software examples and we are developing more every day.


this open source has include all iFrogLab F60 official sample code, 


Supported BLE Central Devices

iOS 7 or 8

*. iPhone 4s
*. iPhone 5/6 (all models)
*. iPod touch 5
*. iPad 3/4/mini/Air

Android 4.3 or above (4.4 recommended for stability) with Bluetooth 4.0 hardware support

*. Nexus 4
*. Nexus 7
*. Samsung Note 3 / GT-I9300 / GT-I9500
*. other compatible Android devices reported by our users 


Windows 8.1 with built-in Bluetooth 4.0 or USB dongle

Mac OSX 10.9.2 with built-in Bluetooth 4.0 or USB dongle

Linux with BlueZ 5.1 with built-in Bluetooth 4.0 or USB dongle


==========================
Q:在 Eclipse  中編譯Android 範例，出現android-support-v7-appcompat錯誤：


A:
那是需要加上Google 的 Library 叫android-support-v7-appcompat.jar， 
如果只是要測試的話，建議可以使用這版本，


設定方法，這看這篇文章
http://oldgrayduck.blogspot.tw/2013/10/android-support-library.html
添加 


另外建議，您可以使用以下的範例，這版本特地拿掉Google 的 Library 會比較容易。

https://github.com/iFrogLab/iFrogLab_F-60_UART/tree/master/sample19-Android-UART-noNeed-android-support-v7-appcompat/ifrogLab_BT_AP_only


