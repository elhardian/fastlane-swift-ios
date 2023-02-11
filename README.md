# CICD FOR SWIFT PROJECT USING FASTLANE

This is sample workflow for Swift project using fastlane for iOS device. This swift project is created by my friend [Edwin](https://www.linkedin.com/in/edwin-niwarlangga-7a2a29b0/). He is a talented iOS developer, I highly recommend him if you need an iOS developer.

Actually this workflows will be used later on my automated test project with iOS device. And the goal of this project is only generate the `.app` file for testing on simulator. If you need more information of deploying to testflight, visit my [Medium](https://elhardian.medium.com/) or go to `./fastlane-testflight` for sample `Fastfile`.

### How it works ?

1. This workflows will clone [swift project repository](https://github.com/leonardusEdwinN/Trending-Git.git)
2. Setup fastlane environment for that project
3. After everything setup, fastlane will build the application with these steps:
    * Pod install   # Installing all required packages
    * Build App     # Build application with xcodebuild
4. Publish `.app` file as artifact


Copyright (c) Lukman Hardian
Unauthorized copying of this file, via any medium is strictly prohibited
Proprietary and confidential
Written by:

* [Lukman Hardian](https://www.linkedin.com/in/lukman-h-b15659123/)