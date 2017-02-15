# USC Mobile App

Built using Apache Cordova. 

Supported Platforms

* iOS

* Android

## Requirements

* Download and install <a href="https://nodejs.org/en/download/current/">Node.js</a>, at least version **4.x.x**. Make sure NPM is at least version **3.x.x**.
* Install <a href="https://cordova.apache.org">Cordova</a> module.
 * For Windows:
 ```
 C:/>npm install -g cordova
 ```
 * For Mac:
 ```
 $sudo npm install -g cordova
 ```

## Installation

* Download or clone repository
* Go into project folder
```
cd USC_Mobile
```
* Add Cordova platforms
 * For iOS:
 ```
 cordova platform add ios --save
 ```
 * For Android:
 ```
 cordova platform add android --save
 ```
 To check if you satisfy requirements for building the platform:
 ```
 cordova requirements
 ```


## Building App
* Run the following command to build project for all platforms:
 ```
 cordova build
 ```

## Deploying App
* For emulator:
```
cordova emulate <platform name>
```
* For device:
```
cordova run <platform name>
```
Example:
```
cordova run android
```
