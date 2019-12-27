# Flutter Cheatsheet

## Basic Commands

**Create a new app**

```` console
flutter create [APP_NAME]
````

```` console
flutter doctor
````

```` console
flutter run
````


**Update existing app.**

```` console
flutter create .
````

**List devices**

```` console
flutter devices
````

*Returns*

```` console

3 connected devices:

Windows    • Windows    • windows-x64    • Microsoft Windows [Version 10.0.18363.535]
Chrome     • chrome     • web-javascript • Google Chrome 79.0.3945.88
Web Server • web-server • web-javascript • Flutter Tools
````

**Run specific device**
Ex. Run Chrome using the second column name.

```` console
flutter run -d chrome
````