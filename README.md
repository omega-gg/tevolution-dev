<a href="https://omega.gg/tevolution"><img src="dist/icon.png" alt="tevolution" width="128px"></a>
---
[![azure](https://dev.azure.com/bunjee/tevolution/_apis/build/status/omega-gg.tevolution)](https://dev.azure.com/bunjee/tevolution/_build)

[tevolution](https://omega.gg/tevolution) is a [Remote Video Screen](https://omega.gg/about/RemoteVideoScreen).<br>
Designed to take streaming requests from a [Semantic Player](https://omega.gg/about/SemanticPlayer).<br>
[omega](https://omega.gg/about) is building tevolution to empower people.<br>

## tevolution
<a href="https://omega.gg/tevolution"><img src="dist/screens/tevolutionA.png" alt="tevolution" width="512px"></a>

tevolution streams videos remotely from a Semantic Player like [MotionMonkey](https://omega.gg/MotionMonkey).<br>
It supports [BitTorrent](https://en.wikipedia.org/wiki/BitTorrent), [Youtube](https://en.wikipedia.org/wiki/Youtube), [Dailymotion](https://en.wikipedia.org/wiki/Dailymotion), [Vimeo](https://en.wikipedia.org/wiki/Vimeo) and [SoundCloud](https://en.wikipedia.org/wiki/SoundCloud).<br>
All of this while serving the end user at all time and without ever showing an ad.<br>

## Technology

tevolution is built in C++ with [Sky kit](https://omega.gg/Sky/sources).<br>

## Platforms

- Windows XP and later.
- macOS 64 bit.
- iOS 64 bit.
- Linux 32 bit and 64 bit.
- Android 32 bit and 64 bit.

## Requirements

- [Sky](https://omega.gg/Sky/sources) latest version.
- [Qt](https://download.qt.io/official_releases/qt) 4.8.0 / 5.5.0 or later.

On Windows:
- [MinGW](https://sourceforge.net/projects/mingw) or [Git for Windows](https://git-for-windows.github.io) with g++ 4.9.2 or later.

Recommended:
- [Qt Creator](https://download.qt.io/official_releases/qtcreator) 3.6.0 or later.

## Building

You can run each step of the build by calling the following scripts:

Install the dependencies:

    sh 3rdparty.sh <win32 | win64 | macOS | iOS | linux | android> [all]

Configure the build:

    sh configure.sh <win32 | win64 | macOS | iOS | linux | android> [sky | clean]

Build the application:

    sh build.sh <win32 | win64 | macOS | iOS | linux | android> [all | deploy | clean]

Deploy the application and its dependencies:

    sh deploy.sh <win32 | win64 | macOS | iOS | linux | android> [clean]

## License

Copyright (C) 2015 - 2020 tevolution authors | https://omega.gg/tevolution

### Authors

- Benjamin Arnaud aka [bunjee](https://bunjee.me) | <bunjee@omega.gg>

### Private License Usage

tevolution licensees holding valid private licenses may use this file in accordance with the private
license agreement provided with the Software or, alternatively, in accordance with the terms
contained in written agreement between you and tevolution authors. For further information
contact us at contact@omega.gg.
