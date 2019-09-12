# Setting up

Alright we have come to maybe the most complex part of learning any development framework, setting everything up. Compared to other frameworks setting up Flutter is way easier since it is distributed as a single archive. Extract it somewhere set the path correctly and you are golden.

### Flutter Distribution

Flutter is distributed as a standalone distribution which self manages itself. It contains the `flutter` binary which handles most of the  house keeping tasks.

### Platform Setup

Flutter is a cross platform development framework, so we need to install the platform for it to work. Flutter supports developing for the web, desktop and mobile. Web and Desktop has not reached stability so this guide would focus more on developing for iOS and Android.

Flutter contains a platform shell and then your cross platform code. To compile the shell we need to setup the build tool-chain for the platform which we are developing. This means we need to setup XCode for iOS and android-studio and associated tools for Android.

### Setup Flutter

Follow the instructions at [https://flutter.dev/docs/get-started/install](https://flutter.dev/docs/get-started/install) and set up flutter for your platform and OS.

### Flutter Binary

You will mostly be interacting with flutter through the `flutter` binary. It's the main bread and butter of Flutter.

It supports a host of commands of which these are the most common ones.

* `flutter` : calls the flutter binary and displays list of options
* `flutter create <app-name>` : creates a new empty app in the given directory
* `flutter run` : runs the current App in an emulator or connected physical device.
* `flutter run --release` : runs the release variant
* `flutter build` : build the Flutter app and generates the release binaries for distribution. 

### 

