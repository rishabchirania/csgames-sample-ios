# CS Games 2016 - Sample iOS App

This project will guide you setting up your environment to build and run a sample iOS application on your local machine.

## Prerequisites

Make sure you have the following software installed before beginning:

- Latest version of Xcode (7.2.1)
- Recent version of the iOS SDK (at least 9.0)

You can download these from the [Apple Developer website](https://developer.apple.com/downloads/).

> **NOTE:** You need a Mac computer running OS X 10.10 or later. If you don't have one, you may check our [Sample Android app](https://github.com/mirego/csgames16-sample-android/), which can be run on Windows, Linux and older versions of OS X.

## Getting started

First, clone the project from Github and move into its directory:

```
git clone git@github.com:mirego/csgames16-sample-ios.git
cd csgames16-sample-ios
```

This project uses [CocoaPods](https://cocoapods.org/) as a dependency manager. If you don't have it already, install it with the following command:

```
gem install cocoapods
```

Then fetch dependencies and build the workspace:

```
pod install
```

When completed, the project should be ready to open:

```
open "Sample App.xcworkspace"
```

## Building the project

In Xcode, run the project by simply pressing the "Play" button on the top left, or by hitting `⌘R`.

<p align="center"><img width="397" src="https://cloud.githubusercontent.com/assets/4378424/13450170/9f948b82-e000-11e5-8270-32423385e7e3.png"></p>

Once the app starts running in the iOS Simulator, your environment is ready for the competition.


## License

This sample app is © 2016 [Mirego](http://www.mirego.com) and may be freely
distributed under the [New BSD license](http://opensource.org/licenses/BSD-3-Clause).
See the [`LICENSE.md`](https://github.com/mirego/csgames16-sample-ios/blob/master/LICENSE.md) file.

## About Mirego

[Mirego](http://mirego.com) is a team of passionate people who believe that work is a place where you can innovate and have fun. We're a team of [talented people](http://life.mirego.com) who imagine and build beautiful Web and mobile applications. We come together to share ideas and [change the world](http://mirego.org).

We also [love open-source software](http://open.mirego.com) and we try to give back to the community as much as we can.