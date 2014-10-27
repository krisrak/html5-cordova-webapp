Make an App from a website
==========================

Cordova template to load a mobile optimized website and package as hybrid app for distribution through App Stores.

This [Intel XDK](http://xdk.intel.com) project can be used to create an app for any mobile optimized website. The project uses Cordova APIs to package into a native app that just loads the specified website. This type of app is recommended for websites built with an app like look-and-feel, responsive, single-page-app with no external website links or redirection. 

This Cordova App template has all the necessary checks to make sure internet connection is available for making website requests. The app template also makes sure that the initial website is loaded completely before displaying to the user using the Cordova InAppBrowser.

App Template Features:
-
- Loads any website in app
- Displays warning with "Retry" button when no internet connection detected
- Loads complete website in background before displaying
- Shows loading splash page while website is loading in background
- Prevents loading "Page not found" when connection is lost during browsing


Cordova Plugins used:
-
- **Device**: `org.apache.cordova.device`
- **Notification**: `org.apache.cordova.dialogs`
- **InAppBrowser**: `org.apache.cordova.inappbrowser`
- **Connection**: `org.apache.cordova.network-information`
- **SplashScreen**: `org.apache.cordova.splashscreen`

How to use:
-
- Download and install [Intel XDK](http://xdk.intel.com)
- Open Intel XDK and select `Open an Intel XDK Project`
- Browse and point to the `webapp.xdk` file
- Open `index.html` and edit the website `var url=` option to a desired website.
- Test in `Emulator` and use `Build` tab to build an app.
