## Demo of Fastlane Plugin altool

This project is a example project that has been used to demo Fastlane Plugin altool_app_type

## Usage

You can checkout this repository or download zip from Github

Set dummy username and password as env varibles. Use Other varibales if you already configured these variables

You can set that easily for bash shell

```
$ export FASTLANE_USER="yourdummy@email.com";
$ export FASTLANE_PASSWORD="testpassword";

```
Now navigate to the project

```
$ cd Altool-Demo
$ bundle install
$ fastlane plugin_altool
```
You will see the failure as I have uploaded dummy IPA file in the build folder but once you got real IPA then this plugin should work
