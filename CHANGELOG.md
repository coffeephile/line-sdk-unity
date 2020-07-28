# Change Log

## 1.1.4

### Fixed

* Add AndroidX flag to gradle property solve dependency issue.

## 1.1.3

### Fixed

* Updated the template gradle build file to make it compile on Unity 2019.3 or later.

## 1.1.2

### Fixed

* An issue which prevents exporting correct Xcode project on Unity 2019.3.

## 1.1.1

### Fixed

* A script problem that prevents Carthage building with Gem version 3.

## 1.1.0

### Added

* Add `IdTokenNonce` to `LoginResult`. This value can be used against the ID token verification API as a parameter.

## 1.0.2

### Fixed

* An issue causes Android build fails due to Editor integrating in some cases. [#9](https://github.com/line/line-sdk-unity/pull/9)

## 1.0.1

### Fixed

* An issue causes the login page cannot dismiss after screen rotation on Android.

## 1.0.0

* Initial release of LINE SDK for Unity.