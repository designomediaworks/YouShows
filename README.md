[apk-url]:        https://github.com/michaelbel/youshows/blob/master/app/release/shows-v1.0.2.apk
[paypal-url]:     https://paypal.me/michaelbel
[github-url]:     https://github.com/michaelbel/youshows
[licence-url]:    http://www.apache.org/licenses/LICENSE-2.0
[googleplay-url]: https://play.google.com/store/apps/details?id=org.michaelbel.shows
[cangelog]:       https://github.com/michaelbel/YouShows/blob/master/CHANGELOG.md
[issue]:          https://github.com/michaelbel/YouShows/issues

[launcher-path]: ../master/app/src/main/res/mipmap-xxxhdpi/ic_launcher.png

[minsdk-badge]:       https://img.shields.io/badge/minSdkVersion-21-0097A7.svg
[paypal-badge]:       https://img.shields.io/badge/Donate-Paypal-0097A7.svg
[license-badge]:      https://img.shields.io/badge/License-Apache_v2.0-0097A7.svg
[arsenal-badge]:      https://img.shields.io/badge/Android%20Arsenal-BottomSheet-0097A7.svg?style=flat
[platform-badge]:     https://img.shields.io/badge/Platform-Android-0097A7.svg
[googleplay-badge]:   https://img.shields.io/badge/Google_Play-Demo-0097A7.svg

<!------------------------------------------------------------------------------------------------------------------------------------->
[![Platform][platform-badge]][github-url]
[![MinSdk][minsdk-badge]][github-url]
[![License][license-badge]][licence-url]
[![GooglePlay][googleplay-badge]][googleplay-url]
[![Paypal][paypal-badge]][paypal-url]

[![Launcher][Launcher-path]][googleplay-url]
# YouShows
Simple app to track and save your TV shows.

## Demo
<a href="https://play.google.com/store/apps/details?id=org.michaelbel.shows" target="_blank">
  <img alt="Get it on Google Play" src="https://goo.gl/cR2qQH" height="100"/>
</a>

## Screenshots
<div style="dispaly:flex">
    <img style="margin-left:0px;" src="/images/render/1.png" width="33%">
    <img style="margin-left:0px;" src="/images/render/2.png" width="33%">
    <img style="margin-left:0px;" src="/images/render/3.png" width="33%">
    <img style="margin-left:0px;" src="/images/render/4.png" width="33%">
    <img style="margin-left:0px;" src="/images/render/5.png" width="33%">
    <img style="margin-left:0px;" src="/images/render/6.png" width="33%">
    <img style="margin-left:0px;" src="/images/render/7.png" width="33%">
    <img style="margin-left:0px;" src="/images/render/8.png" width="33%">
    <img style="margin-left:0px;" src="/images/render/9.png" width="33%">
</div>

## Build
[tmdb-introduction]: https://developers.themoviedb.org/3/getting-started/introduction
Take a look at `local.properties` and fill it with [your own][tmdb-introduction] `tmdb_api_key`.

## Features
* Material design
* Sorting shows
* Search history
* Themes

## Permissions
* android.permission.VIBRATE
* android.permission.INTERNET
* android.permission.BODY_SENSORS
* android.permission.ACCESS_WIFI_STATE
* android.permission.ACCESS_NETWORK_STATE
* android.permission.READ_EXTERNAL_STORAGE
* android.permission.WRITE_EXTERNAL_STORAGE

## Libraries
* [BottomSheet](https://github.com/michaelbel/BottomSheet)
* [Gson](https://github.com/google/gson)
* [Retrofit](https://github.com/square/retrofit)
* [Picasso](https://github.com/square/picasso)
* [RxJava](https://github.com/ReactiveX/RxJava)
* [Realm](https://github.com/realm/realm-java)
* [ExpandableTextView](https://github.com/Blogcat/Android-ExpandableTextView)
* [CircleProgressView](https://github.com/jakob-grabner/Circle-Progress-View)

## Issues
If you find any problems or would like to suggest a feature, please feel free to file an [issue][issue].

## Changelog
Cangelog is available [here][cangelog].

## License
<a href="http://www.apache.org/licenses/LICENSE-2.0" target="_blank">
  <img alt="Apache License 2.0" src="https://github.com/michaelbel/YouShows/blob/master/images/apache_software_foundation_logo.png" height="120"/>
</a>

    Copyright 2017 Michael Bely

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
