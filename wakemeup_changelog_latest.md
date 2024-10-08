# 2024.03

* __[FIX]__ Fixed an issue with the date picker on small resolutions. 
* __[FIX]__ Improved performances and other small bugfixes.

# 2024.02

* __[FIX]__ Fixed an issue with calendar synchronization for alarms that are activated or deactivated based on a calendar. 
* __[FIX]__ Fixed an issue with alarms not always receiving a Dismiss or Snooze event from Tasker. 
* __[FIX]__ Fixed some crashes specific to Samsung devices.
* __[FIX]__ Improved performances and other small bugfixes.

# 2024.01

* __[NEW]__ Added a warning about Adaptative Battery being enabled
* __[NEW]__ New ringtone picker. This will fix issues related to ringtone selection not working when the ringtone picker is not set as default.
* __[NEW]__ Performance improvements.
* __[NEW]__ When a device kills the application (adaptative battery, battery saver...), a new option now permits to register again all alarms every hour (General settings -> Advanced options -> Force register background services every hour). This does not guarantee that a battery saver won't kill the alarm before it goes off, but it should help.
* __[FIX]__ Added a button to clear Text-to-Speech messages
* __[FIX]__ Fixed a crash when trying to select a directory on devices without any file manager
* __[FIX]__ Fixed an alarm keeping ringing indefinitely when the notification is dismissed by a user on Android 14. It should not be possible to dismiss the notification, but Android 14 changed this behavior. 
* __[FIX]__ Moved ads position to comply to Google's guidelines
