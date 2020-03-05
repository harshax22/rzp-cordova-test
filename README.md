# Razorpay Cordova Sample Application[Demo Account][iOS Setup]

This is a sample app created on Cordova using Razorpay's official Cordova SDK

### Prerequisites

```
Install Xcode and Cordova on your system.
```

### Installing

Navigate to the directory of the project and run the followning command

```
npm install
```

Navigate to the ios directory in the platforms folder and build the .xcworkspace file using the following command

```
cordova build ios
```


## Running the App

Cmd + R should run the application once build is successful. Click on the Payment button that opens the checkout. 
Based on the callback(success / failure) relevant event handlers would be called. 

## Point to Note

In case you're seeeing an error along the lines of dyld: Library not loaded: @rpath/Razorpay.framework/Razorpay
Please Embed and Sign the Razorpay.Framework from the General Settings in Xcode. 
