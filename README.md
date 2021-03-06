# dennism-location-sms-googlemaps-android

A fast way to get started with the [Google Maps Android API v2](http://developers.google.com/maps/documentation/android).

## How to setup and run the application 
.Clone the repo on your local machine

.Copy the project files into your android studio  project directory.

.Open the project.

.Run on android phone or android emulator

# TOC

  * [Requirements](#requirements)
  * [Android Studio](#android-studio)
    * [Download Android Studio](#download-android-studio)
    * [Open the project](#open-the-project)
    * [Add your API key](#add-your-api-key)
    * [Run the app](#run-the-app)
    * [Troubleshooting](#troubleshooting)

# Requirements

Java Development Kit (JDK) [Download](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)

Android SDK [Download](http://developer.android.com/sdk/index.html)

# Android Studio

## Download Android Studio
Download Android Studio (http://developer.android.com/sdk/index.html)

## Open the project
  1. On the welcome screen, select "Open an existing Android Studio project" or if you have a project open, choose "File->Open...""
  2. Navigate to the checked out project
  3. Press "Ok"

## Add your API key
  1. Navigate to google_maps_api.xml
  2. Replace "your_api_key" with an API key generated using [these instructions]
  (https://developers.google.com/maps/documentation/android/start#the_google_maps_api_key)

## Run the app
  1. Ensure your phone is in plugged in, developer mode enabled and screen unlocked
  2. Press the green arrow, or choose Run>Run

## Troubleshooting
### I see a grey map
Follow the instructions under "Add your API key" and try again. The logcat output will also
provide useful information if there is a configuration issue with the package name, signing
certificate or API key.
