# CICD FOR SWIFT PROJECT USING FASTLANE

This is sample workflow for Swift project using fastlane for iOS device. This swift project is created with [Firebase Starter App](https://iosapptemplates.com/templates/swiftui-firebase).

Actually this workflows will be used later on my automated test project with iOS device. And the goal of this project is only generate the `.app` file for testing on ios simulator.

### How it works ?

1. Setup fastlane environment
2. After everything setup, fastlane will build the application with these steps:
    * Pod install   # Installing all required packages
    * Build App     # Build application with xcodebuild
3. After finish, The build output should be in this dir `./build`


Copyright (c) Lukman Hardian
Unauthorized copying of this file, via any medium is strictly prohibited
Proprietary and confidential
Written by:

* [Lukman Hardian](https://www.linkedin.com/in/lukman-h-b15659123/)