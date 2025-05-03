# 2025.05

* __[FIX]__ New option: add a delay to the music ringtone playback. Starting with Android 15, music ringtones may not play. This new setting is available in the general settings, “Other” subsection. It will help making sure that music files playback starts as it should. Please activate this option if and only if you have issues with music file playback.


* __[NEW]__ Android 15 support. 
* __[NEW]__ New Swedish translation. Thanks to Johan Wetterberg.
* __[FIX]__ Xiaomi devices needs additional permissions for the application to work correctly. Those permissions are now correctly asked when opening the application. Disabling MIUI optimizations on Xiaomi devices is still necessary and cannot be done from the application.
* __[FIX]__ Time displayed on the notifications when on a different timezone is now correct.
* __[FIX]__ Fixed issues with Calendar-based alarms with devices that do not conform to Android specications, like Xiaomi devices.
* __[FIX]__ Fixed frequent alarms scheduling. 
* __[FIX]__ Fixed an issue with the "When time changed" event. It is now correctly fired when the time of a scheduled alarm is changed manually.
* __[FIX]__ Fixed an issue with scheduled alarms which activates depending on calendar events, when it just went off, was dismissed and there was no other event.
* __[FIX]__ It was possible to delete a locked alarm.
* __[FIX]__ Improved performances.

* __[REMOVED]__ Removed the option to force an alarm to go fullscreen as Android prevents it to work starting with Android 10.
