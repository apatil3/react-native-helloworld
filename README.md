# react-native-helloworld
An example project incorporating the MotionDNA framework into a universal android/ios react native application
## Setup
Before attempting to run this demo please make sure that you have taken care of the following dependencies

Ensure that you have [node](https://nodejs.org/en/download/) installed and then use npm to install react native as described below

### Installing node
The simplest way to get started is to install [homebrew](https://brew.sh) on your system.
You can then install node and watchman with the following commands
```
brew install node
brew install watchman
```

### Installing React-Native Command Line Interface
You may install react-native with the following npm command
```
npm install -g react-native-cli
```
once this is complete, navigate to this projects folder and type ```npm install``` to install all dependencies listed in the project's package.json file

### Configuring the environments for iOS and Android

__iOS (XCode)__

Navigate to project ios subfolder and run
```
pod install
```
to install the latest iOS MotionDNA SDK

__Android (Android Studio)__

Open the Android project folder in Android Studio
Aside from instant run, install any recommended dependencies and build tools that are suggested


## Running the demos
The hello world project is designed to work with both ios and android systems. It will run on the simulator or the actual device.

You can start streaming the app to your device with the following commands

__For iOS__

```
react-native run-ios
```
For iOS you will probably want to have the simulator open already as XCode 9 does not start the simulator automatically with this command

__For Android__

```
react-native run-android
```
Be sure you have the android platform-tools in your PATH environment variable so that react can access tools like adb to run your app. You may need to setup a virtual device first if you wish to use the simulator.

You may also run either app by using the standard build and run tools in each platforms respective IDE

if you have any questions please feel free to reach out to support@navisens.com 

