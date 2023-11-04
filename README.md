# Boilerplate Code for Swift
This repo serves as a tool for both old and new iOS developers. Every project needs tools to ease early development phases.
The design of this is to jump start development projects.
While this could have been developed using an Xcode project and added using Cocoapods or SwiftPackageManager, it is designed to simply be folders of tool files that you can download into your project.

[Utilities](#utilities)
[UIKit+](#uikit+)

## Utilities
#### Alert
This tool utilizes UIAlertController to display alerts on the given ViewController. While this comes with standard alerts (OK, Destructive, Decision) these can be edited and more can be added.
#### KeyboardToolbar
Easily adds a toolbar to the keyboard including the arrows that can move to the previous or next textfield.
#### OpenLink
Easily open links in an externally browser once you add the links to your enum. Make sure to edit this and make security updates if necessary.

## UIKit+
Most of UIKit holds base variables that we want to expand when developing our projects. Here are a few tools added to UIKit to decrease written code and increase productivity.
#### BiometricUnlock
A pre-written tool that will use local authentication to authenticate the user. If using a username and password for your users, you must first provide a way to authenticate the user using a username and password before enabling local authentication.
