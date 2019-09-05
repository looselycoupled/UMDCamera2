# UMDCamera2

This repository contains Android application code for taking raw images in support of academic research.  It is based off of the sample code released by Google at https://github.com/googlesamples/android-Camera2Basic.

## Setup

Open this project in Android Studio and ensure you have the required framework libraries installed.  Verify your target version, build tools version, compiled sdk version, etc. and you should be able to build and install onto a local Android phone.

**Note** that this codebase has only been tested on the Samsung Galaxy S6.

## Usage

As of September 2019, the app allows you to take a series of raw image captures on a periodic schedule ranging from 1 to 10 minutes.  Once started, it will continue to take a picture until there is no more usable storage.  During capture, press the "Cancel" button at any time to end the automated capture.