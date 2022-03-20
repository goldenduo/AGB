<h1 align="center">
  <img src="https://selfshare.shenqikeji.top/AGB/icon.png" alt="AGB" width="200">
  <br>AGB<br>
</h1>

<h4 align="center">A bridge for Android.</h4>

## Introduction

AGB is short for Android Great Bridge.It does not require any _root_ access neither on the device nor on the computer. 
* It provides **reverse tethering** over `adb` for Android: it allows devices to use the internet connection of the computer they are plugged on. 
* It provides **display and control** of Android devices connected via USB (or over TCP/IP).
* It **forwards audio** from an Android 10 device to the computer. 

## Features

### 1. Reverse Tethering

- **Fully stack support:** IPv4/IPv6/TCP/UDP
- **GUI support:** Beautiful and easy-to-use interface,bid farewell to the command line
- **Multiple devices:** Multiple devices can be connected at the same time
- **Multiple OS:** It works on _GNU/Linux_, _Windows_ and _Mac OS_.

### 2. Display and Control

- **lightness**: native, displays only the device screen
- **performance**: 30~120fps, depending on the device
- **quality**: 1920×1080 or above
- **low latency**: [35~70ms][lowlatency]
- **low startup time**: ~1 second to display the first image

### 3. Forwards audio

It may only forward audio from apps which do not [prevent audio
capture][allow]. The rules are detailed in [capture policy][rules]:

> - By default, apps that target versions up to and including to Android 9.0 do
>   not permit playback capture. To enable it, include
>   `android:allowAudioPlaybackCapture="true"` in the app's `manifest.xml` file.
> - By default, apps that target Android 10 (API level 29) or higher allow their
>   audio to be captured. To disable playback capture, include
>   `android:allowAudioPlaybackCapture="false"` in the app's `manifest.xml`
>   file.

So some apps might need to be updated to support audio capture.

[allow]: https://developer.android.com/guide/topics/media/playback-capture#allowing_playback_capture
[rules]: https://developer.android.com/guide/topics/media/playback-capture#capture_policy

## Requirements

The Android application requires at least API 23 (Android 6.0).

## Run (simple)

1、Turn on [USB debugging](https://github.com/goldenduo/AGB/blob/main/developer_options.md) in the settings and
connect USB

2、Run AGB and click the button on the right

![guide](https://cdn.jsdelivr.net/gh/goldenduo/AGB/R/guide.gif)

3、The very first start should open a popup to request permission

![request](https://cdn.jsdelivr.net/gh/goldenduo/AGB/R/request.jpg)

## Download

From GitHub：

- [Windows](https://github.com/goldenduo/SelfShare/raw/main/AGB/windows/agb2.zip)
- [MacOS](https://github.com/goldenduo/SelfShare/raw/main/AGB/macos/agb2.zip)
- [Linux](https://github.com/goldenduo/SelfShare/raw/main/AGB/linux/agb2.zip)

From CDN：

- [Windows](https://selfshare.shenqikeji.top/AGB/windows/agb2.zip)
- [MacOS](https://selfshare.shenqikeji.top/AGB/macos/agb2.zip)
- [Linux](https://selfshare.shenqikeji.top/AGB/linux/agb2.zip)

## Status

AGB is constantly adding features.

## Donate

- Star AGB to make it go further

![request](https://cdn.jsdelivr.net/gh/goldenduo/AGB/R/please.gif)

- Donation List

  - @mike 188yuan

- Thanks for donating! 

<img src="https://cdn.jsdelivr.net/gh/goldenduo/AGB/R/alipay.jpg" width="270" height="420">

## Contact

Email: goldenduo@qq.com

