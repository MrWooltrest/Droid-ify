<div align="center">

<img width="17%" src="app/src/main/res/mipmap-xxxhdpi/ic_launcher_round.png" alt="Droid-ify" align="center">

# Droid-ify

### A quick material F-Droid client

[![GitHub repo stars](https://img.shields.io/github/stars/Iamlooker/Droid-ify?style=flat)](https://github.com/Iamlooker/Droid-ify/stargazers)
[![GitHub License](https://img.shields.io/github/license/Iamlooker/Droid-ify)](https://github.com/Iamlooker/Droid-ify/blob/master/COPYING)
[![GitHub All Releases](https://img.shields.io/github/downloads/Iamlooker/Droid-ify/total.svg)](https://github.com/Iamlooker/Droid-ify/releases/)
[![GitHub release](https://img.shields.io/github/v/release/Iamlooker/Droid-ify?display_name=tag)](https://github.com/Iamlooker/Droid-ify/releases/latest)
[![Small translation badge](https://hosted.weblate.org/widgets/droidify/-/localization/svg-badge.svg)](https://hosted.weblate.org/engage/droidify/?utm_source=widget) 

[<img src="https://gitlab.com/IzzyOnDroid/repo/-/raw/master/assets/IzzyOnDroid.png"
alt="Get it on IzzyDroid"
width="48%">](https://android.izzysoft.de/repo/apk/com.looker.droidify)
[<img src="https://fdroid.gitlab.io/artwork/badge/get-it-on.png"
alt="Get it on F-Droid"
width="48%">](https://f-droid.org/packages/com.looker.droidify)
[<img src="https://github.com/WeblateOrg/weblate/blob/main/weblate/static/weblate.svg"
alt="Weblate"
width="40%">](https://hosted.weblate.org/projects/droidify/localization/)
&nbsp;&nbsp;
[<img src="https://upload.wikimedia.org/wikipedia/commons/8/82/Telegram_logo.svg"
alt="Join Telegram Channel"
width="30%">](https://t.me/droidify)

<div align="left">

## :book: Features

* :sparkles: Material F-Droid style
* :flower_playing_cards: No cards or inappropriate animations
* :rocket: Fast repository syncing
* :jigsaw: Standard Android components and minimal dependencies

## :framed_picture: Screenshots

### :sun_with_face: Light Theme

| <img src="metadata/en-US/images/phoneScreenshots/home-light.png" width="500" align="center"/> | <img src="metadata/en-US/images/phoneScreenshots/app-light.png" width="500" align="center"/> |
|:---:|:---:|

### :last_quarter_moon_with_face: Dark Theme

| <img src="metadata/en-US/images/phoneScreenshots/home-dark.png" width="500" align="center"/> | <img src="metadata/en-US/images/phoneScreenshots/app-dark.png" width="500" align="center"/> |
|:---:|:---:|

### :new_moon_with_face: Black Theme

| <img src="metadata/en-US/images/phoneScreenshots/home-amoled.png" width="500" align="center"/> | <img src="metadata/en-US/images/phoneScreenshots/app-amoled.png" width="500" align="center"/> |
|:---:|:---:|

## :building_construction: Building from source

Specify your Android SDK path either using the `ANDROID_HOME` environment variable, \
or by filling out the `sdk.dir` property in `local.properties`.

### :pen: Signing

Can be done automatically using `keystore.properties` as follows:

```properties
store.file=/path/to/keystore
store.password=key-store-password
key.alias=key-alias
key.password=key-password
```

### :bricks: Building

Run `./gradlew assembleRelease` to build a release package or run `./gradlew assembleDebug` if you want to build a debug APK.

All of these packages can be installed using the Android package manager.

## :eye_speech_bubble: Translations [<img align="right" src="https://hosted.weblate.org/widgets/droidify/-/localization/287x66-grey.png" alt="Translation status" />](https://hosted.weblate.org/engage/droidify/?utm_source=widget)

[Translate Droid-ify on Hosted Weblate](https://hosted.weblate.org/engage/droidify/). \
[![Translation status](https://hosted.weblate.org/widgets/droidify/-/multi-auto.svg)](https://hosted.weblate.org/engage/droidify/?utm_source=widget)

### You can always add other lanuages

## :scroll: License [<img align="right" src="https://www.gnu.org/graphics/gplv3-with-text-136x68.png" alt="GPLv3" />](/COPYING)

Licensed under [GPLv3+](/COPYING) \
Direct Adaptation/Modification of [Foxy-Droid](https://github.com/kitsunyan/foxy-droid/). \
Copyright © 2020–2022 [Iamlooker](https://github.com/Iamlooker) and [contributors](https://github.com/Iamlooker/Droid-ify/graphs/contributors).
