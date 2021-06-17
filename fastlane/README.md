fastlane documentation
================
# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```
xcode-select --install
```

Install _fastlane_ using
```
[sudo] gem install fastlane -NV
```
or alternatively using `brew install fastlane`

# Available Actions
## iOS
### ios create_app
```
fastlane ios create_app
```
Create app on Apple Developer and App Store Connect
### ios sync_profiles
```
fastlane ios sync_profiles
```
Sync certificates
### ios build
```
fastlane ios build
```
Create ipa
### ios beta
```
fastlane ios beta
```
Upload to TestFlight
### ios screenshot
```
fastlane ios screenshot
```
Take screenshots
### ios upload
```
fastlane ios upload
```
Upload to App Store
### ios release_app
```
fastlane ios release_app
```
Create app, screenshot ,build and upload

----

This README.md is auto-generated and will be re-generated every time [fastlane](https://fastlane.tools) is run.
More information about fastlane can be found on [fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
