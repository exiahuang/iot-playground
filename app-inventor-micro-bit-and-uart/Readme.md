https://community.appinventor.mit.edu/t/app-inventor-micro-bit-and-uart/44876



## App Inventor, Micro:bit and UART

*Somehow, communicating with a micro:bit via UART is more difficult than it should be. For now, using the extensions as indicated in this tutorial, will ensure that everything works.*

This tutorial is intended to show how to use Bluetooth Low Energy (BLE) to send messages to a micro:bit. This can be used to control a toy robot car or any device that uses a micro:bit as its brain.

This first part will only cover the basic communication with a micro:bit via BLE. A follow up tutorial will cover controlling a robot car, for example the Ring:bit car v2 or the DFRobot Maqueen, both available for less than 30$, not including a micro:bit, which should cost less than 20$ for a v2 version.

The micro:bit is an electronics board, intended for schoolchildren, to learn programming and simple electronics. It is also nice to use as the heart of a little robot. To be able to control this robot via App Inventor we need UART communication, which is not so easy to do.
![Snap25](https://community.appinventor.mit.edu/uploads/default/original/3X/d/e/defe2da143adbd0d94ed0b4848b66054f1306ad7.png)
Here is a pdf with the text of the tutorial:
[microbitUART.pdf](https://community.appinventor.mit.edu/uploads/short-url/a4fSZlCRbX2MUCNfdJU5Gw0S3Xp.pdf) (1.6 MB)
Here are the links you need:
[com.bbc.microbit.profile.aix](https://community.appinventor.mit.edu/uploads/short-url/zuppqyO1Hya0lujGfQZeU4oMLfS.aix) (100.7 KB)
[BTstarter.aia](https://community.appinventor.mit.edu/uploads/short-url/mTBZ9y7Bs6UaT3YRb70XerVV2pl.aia) (191.3 KB)
[BTReadWrite.aia](https://community.appinventor.mit.edu/uploads/short-url/8cPjPsQQYG0c9GtI7Msft6IjelA.aia) (291.2 KB)
[microbit-UART_RW.hex](https://community.appinventor.mit.edu/uploads/short-url/sBlb9P1OPHwGtg2J9QT1NH3Mx1N.hex) (1.5 MB)

Due to changes in the permission systen for Android, there is an updated BLE extension, at this moment still in beta:
[edu.mit.appinventor.ble-20230223-beta.aix](https://community.appinventor.mit.edu/uploads/short-url/qwUK7QFd6yRCXbnoRt8ItR01MgF.aix) (200.0 KB)
Here is the app, updated with the newer extension:
[BTReadWrite_2.aia](https://community.appinventor.mit.edu/uploads/short-url/y238CkbsWPsvOjdjGJ8GNcApn1Q.aia) (295.4 KB)
You will need this version when your phone is running Android 12 and up. Be sure also to have Location set to on in the settings of your phone.





