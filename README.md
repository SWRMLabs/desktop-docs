
#### October 2020 (version 1.0.18)

Here are the highlights:

* **Size**: 
   Windows - 82.4 MB
   Linux - 74.4 MB
   Mac -  120 MB
* **Date**: 23 October 2020

**Improvements / Features**

1. Display banner continuously in Hive app until the user's port is forwarded.
2. Notification is integrated, user can see all the notification in header on click of bell icon.
3. Important notification will display in OS notification.
4. On first start our application will redirect to settings page.
5. Clear all notification button on the top left of notification header.
6. Clear notification each at a time.
7. If daemon is crashed, restart the daemon automatically.
8. App status will show immediate result if user stopped daemon directly from the cli.
9. Correct status display on settings page port is available or not
10. Link is attached on explaining the procedure of port forwarding.
11. Auto-update feature (Windows & Mac OS only) installs the latest version of the Hive application automatically. 
12. Auto-update fails (Windows & Mac OS only) due to any issue (network disconnect or auto-update error) we will download again and display new version to user.
13. Device name is registered with user's system name. 

**Known Issues**

1. Intermittent failure to start daemon automatically after changing storage folder location to new path and reload. 
2. Systems didn't met the minimum specified requirements of SWRMLabs, delay in responses will see while using Hive application
