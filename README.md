# ionic-3-camera-app
Using Ionic 3 to build an app that utilize the camera module of the phone.
This repo was referred and modified from [Ionic 2: Using Camera with Ionic Native](http://blog.ionic.io/10-minutes-with-ionic-2-using-the-camera-with-ionic-native/)

Created by: Pinetop Technology

<img width="900px" height="500px" src="http://www.pinetoptechno.com.my/wp-content/uploads/2017/05/camera-app-full.jpg" />

In order to run this, following steps are required.

Run 'ionic serve'

It will prompt you to install @ionic/cli-plugin-ionic-angular, 



We’ll start by creating an app with the blank template using ionic start.

ionic start cameraApp blank --v2 

If you have not yet installed Cordova, you’ll need to do that before completing this tutorial. This may require adding sudo before the command.

npm install -g cordova

After changing into our app directory (cd cameraApp), you’ll want to add a platform for your app.

ionic cordova platform add android

ionic cordova plugin add cordova-plugin-camera



