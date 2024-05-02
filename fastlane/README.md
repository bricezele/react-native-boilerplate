fastlane documentation
----

# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```sh
xcode-select --install
```

For _fastlane_ installation instructions, see [Installing _fastlane_](https://docs.fastlane.tools/#installing-fastlane)

# Available Actions

## Android

### android firebase

```sh
[bundle exec] fastlane android firebase
```

Android Build (development) and Deploy to Firebase App Distribution

### android beta

```sh
[bundle exec] fastlane android beta
```

Android Beta - Bundle development and Deploy to Play Store Beta

### android production

```sh
[bundle exec] fastlane android production
```

Android Release Build and Deploy to Play Store Production

----


## iOS

### ios firebase

```sh
[bundle exec] fastlane ios firebase
```

iOS Build and Deploy to Firebase App Distribution

### ios testflight

```sh
[bundle exec] fastlane ios testflight
```

iOS Build and Deploy to TestFlight

### ios production

```sh
[bundle exec] fastlane ios production
```

iOS Build and Deploy to App Store

----

This README.md is auto-generated and will be re-generated every time [_fastlane_](https://fastlane.tools) is run.

More information about _fastlane_ can be found on [fastlane.tools](https://fastlane.tools).

The documentation of _fastlane_ can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
