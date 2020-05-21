## HUAWEI Awareness Kit Sample Code

## Contents

- [Overview](#overview)
- [Getting Started](#getting-started)
- [Running Environment](#running-environment)
- [Sample Code](#sample-code)
- [License](#license)

## Overview

The sample code shows how to use the Capture API and Barrier API of HUAWEI Awareness Kit for quick integration.

## Getting Started

For more development details, please refer to the following link:

Development Guide:https://developer.huawei.com/consumer/en/doc/development/HMS-Guides/awareness-introduction

API References:https://developer.huawei.com/consumer/en/doc/development/HMS-References/awareness

We also provide an example to demonstrate the use of Awareness SDK for Android.

This sample uses the Gradle build system.

First download the demo by cloning this repository or downloading an archived snapshot.

In Android Studio, use the "Open an existing Android Studio project", and select the directory of "awareness-sample".

You should create an app in AppGallery Connect, and obtain the file of agconnect-services.json and add to the project. You should also generate a signing certificate fingerprint and add the certificate file to the project, and add configuration to build.gradle. See the [Configuring App Information in AppGallery Connect guide](https://developer.huawei.com/consumer/en/doc/development/HMS-Guides/awareness-preparation) to configure app in AppGallery Connect.

## Running Environment

Android Studio and JDK 1.8 are used for coding.

To run the app generated by the sample code on a mobile phone, you need to use a mobile phone meeting the following requirements: the EMUI version is 9.1 or later or the Magic UI version is 2.1 or later; the chip version is Kirin 810, Kirin 980, Kirin 990, or later.

## Sample Code

The HUAWEI Awareness Kit sample code includes Capture and Barrier API sample code.

Capture APIs can be called to obtain the time, headset, location, activity, ambient light, weather, bluetooth car stereo, and beacon status.
Capture APIs allow your app to request the status of a user. For example, the getHeadsetStatus() API can be used to obtain connection status of the headset.

For details about Capture APIs, please visit https://developer.huawei.com/consumer/en/doc/development/HMS-References/awareness-captureclient.

Barrier APIs can be called to implement awareness of the time, headset, location, activity, ambient light, Bluetooth car stereo, and beacon status.
Barrier APIs allow your app to set a series of awareness states. When a user enters a set state, Awareness Kit triggers the corresponding callback to notify the app. For example, the LocationBarrier.enter() API can be used to create a geo-fence.When the user enters the area specified by the geo-fence, Awareness Kit triggers the corresponding callback to notify the app.

For details about Barrier APIs, please visit https://developer.huawei.com/consumer/en/doc/development/HMS-References/awareness-barrier.

## License

HUAWEI Awareness Kit sample is licensed under the [Apache License, version 2.0](http://www.apache.org/licenses/LICENSE-2.0).
