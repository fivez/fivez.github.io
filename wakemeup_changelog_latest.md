# 2024.01 Beta

* __[NEW]__ Added a warning about Adaptative Battery being enabled
* __[NEW]__ New ringtone picker. This will fix issues related to ringtone selection not working when the ringtone picker is not set as default.
* __[NEW]__ Performance improvements.
* __[NEW]__ When a device kills the application (adaptative battery, battery saver...), a new option now permits to register again all alarms every hour. This does not garranty that a battery saver won't kill the alarm before it goes off, but it should help.

* __[FIX]__ Added a button to clear Text-to-Speech messages
* __[FIX]__ Fixed a crash when trying to select a directory on devices without any file manager
* __[FIX]__ Fixed an alarm keeping ringing indefinitely when the notification is dismissed by a user on Android 14. It should not be possible to dismiss the notification, but Android 14 changed this behavior. 

# 2023.04

* __[FIX]__ Fixed progressive brightness
* __[FIX]__ Fixed ringtones with Text-to-Speech when using Gentle Wake Up
* __[FIX]__ Fixed a few more bugs