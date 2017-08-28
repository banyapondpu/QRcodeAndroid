# QRcodeAndroid
Basic library for Android QRCode Reader from Google open source and customize code

How to setup this repo:

<code>git clone https://github.com/banyapondpu/QRcodeAndroid.git</code>

copy folder "qrcode" and "camera" to you package same "MainActivity.java" file.

In your build.grade (Module: App) predefine with dependency:

<code>compile 'com.google.android.gms:play-services-vision:10.2.6'</code>

Allow Camera permission in AndroidmaniFest.xml file with:

<code>
android.permission.CAMERA
</code>
<code>
android.permission.WRITE_EXTERNAL_STORAGE
</code>

