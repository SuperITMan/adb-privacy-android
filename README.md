# About

This repo is simply there to help to improve the control of your phone without risk :happy:i

What I want is actually really simple. Create small which uses adb with a GUI to play with thoses options easily.

# TODO

[ ] Run a pc app
[ ] Display all installed app on the Android + their background status
[ ] Thanks to checkboxes, select multiple apps to change their status


## Commands

> adb shell pm list package

This method simply list all the packages you have installed on your Android phone.

Based on [RunInBackgroundPermissionSetter](https://github.com/MrBIMC/RunInBackgroundPermissionSetter) project, here are the main commands to know.

> adb shell cmd appops set \<package_name\> RUN_IN_BACKGROUND ignore

This command will prevent the application running in background.

> adb shell cmd appops set \<package_name\> RUN_IN_BACKGROUND allow

This command is exactly the same but its goal is to authorize the app to run in background.##
