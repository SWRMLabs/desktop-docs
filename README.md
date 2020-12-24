#### December 2020 (version 1.0.20)
 
Here are the highlights:
 
* **Size**: 
   Windows - 82.4 MB
   Linux - 74.4 MB
   Mac -  120 MB
* **Date**: 24 December 2020
 
**Improvements / Features**
 
1. Display banner continuously in Hive app until the user's port is forwarded.
2. Notification system integrated. User can see all the notifications in header.
3. Important notifications will display in OS.
4. On start of application user will be redirected to settings page.
5. Clear all notifications button implemented on the top left of notification header.
6. Clear notifications one at a time functionality
7. If daemon crashes, daemon is restarted automatically.
8. App status will display immediate result if user stops daemon directly from the cli.
9. Correct status display in settings page of port availability
10. Link attached to explain the procedure of port forwarding.
11. Auto-update feature (Windows & Mac OS only) installs the latest version of the Hive application automatically. 
12. If auto-update fails (Windows & Mac OS only) due to any issue (network disconnect or auto-update error), we will download again and display new version to user.
13. Device name is registered with user's system name. (Some systems which couldn't get system's device will have "default" name which can modified in Settings page)
14. Some minor code enhancements and bug fixes. 
 
**Known Issues**
 
1. Intermittent failure to start daemon automatically after changing storage folder location to new path.
2. Systems that don't meet the minimum specified requirements of SWRM Labs will experience a delay in responses while using the Hive application
3. Sometimes while the device is busy, exiting the application may take up to 60 seconds. 
