android-4.4-phonegap-file-upload
================================

Sample project for demonstrating how to enable file uploads from Android 4.4+ webview (Phonegap)


To use this example, create a new phonegap project:

    \#cordova create webview-upload com.precambria.webview-upload WebviewUpload

Add the camera plugin:

    \#cordova plugin add org.apache.cordova.camera

Replace the generated www folder with the contents of this repo, then add the Android platform:

    \#cordova platform add android

deploy it to your device:

    \#cordova run android