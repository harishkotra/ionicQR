# ionicQR

Generate and scan QR codes using an Ionic App in both iOS and Android 

## Plugins Used

[ngx-qrcode2](https://www.npmjs.com/package/ngx-qrcode2) - An Angular 4 Component library (now updated to Angular 5) for Generating QR (Quick Response ) Codes.
[Phonegap Barcode Scanner Plugin](https://github.com/phonegap/phonegap-plugin-barcodescanner) - Cross-platform BarcodeScanner for Cordova / PhoneGap

### Demo

![IonicQR Demo - Desktop to generate the QR Code](https://i.imgur.com/2gJ3H7M.png)
![IonicQR Mobile App Preview](https://i.imgur.com/mbhofPt.jpg)
![IonicQR Mobile App Scan Result](https://i.imgur.com/DEb5rWL.jpg)

### Installation

This app requires [Node.js](https://nodejs.org/) v7+, cordova and ionic framework to run.
Install the dependencies and build the app. 

```sh
$ git clone https://github.com/harishkotra/ionicQR.git
$ cd ionicQR
$ npm install -d
$ ionic cordova platform add android/ios
$ ionic cordova run/build android 
```

**Free Software, Hell Yeah!**

**Credits:** Built using this [tutorial](https://ionicacademy.com/ionic-qr-code-generator-reader/)
