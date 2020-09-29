
#### September 2020 (version 1.0.8)

Here are the highlights:

* **Size**: 
   Windows - 82.4 MB
   Linux - 74.4 MB
   Mac -  120 MB
* **Date**: 28 September 2020

**Improvements**

* Auto-update feature added
* Port forwarding checker
* App size reduced
* Send OTP via sms
* GRPC event integration (polling removed)
* Storage size validation (if you utilize your storage and then try to reduce size then an error is thrown)
* Uptime percentage sync with cli
* Rebranding change
    Cacher Desktop Application-streamspace => Hive Desktop app - SWRM Labs
    SSH => SWRM
    Streamspace => SWRM Labs
    Cacher => Hiver
    Icon changes
* Download Queue issue resolved when storage is not available
* Upload Queue issued resolve when storage is not available
* After loading, login will not appear if user is already logged in

**UI FIXES**
1. White header icon left margin
2. Dashboard dynamic font size
3. Node page card height equalized
4. Wallet page card height increased
5. Wallet page dynamic font
6. Earnings page dynamic font
7. Earnings page graph height improved
8. Earnings page alignment enhanced
9. Logo for Earnings page
10. Bandwidth over time- small screen alignment issue
11. All index.html CDN links made as local assets (except CDN icons)
12. Software update modal sized, font style, centered
13. Refer friend modal input field, position improved
14. Fileshare UI - drag files height, space between icon and text retrieve file button enhanced
15. File hash input field fixed
16. Close icon in modals
17. New Hive logo added


**Bug Fixes**

* CLI event integration with desktop application
* Confirmation required before deleting a file
* UI issues in desktop app
* Refer friend functionality
* Upon pinging url of software- update not found
* Upload queue allows duplicate file entries (intermittent)
* Upload stuck at 0% if the file is uploaded when daemon is not running
* Added tab in the taskbar to display connection status
* Resizing of fixed width in windows 
* Earnings page calculation by uploading files to Customer 
* Intermittent behaviour of timer stuck at 00:00:00 
* Kill all processes after successful daemon stop 
* Added daemon check to add file
* Added loader while paused
* Adding loader while paused from tray
* Start & Stop are dependent on timer 
* Kill PID after daemon stopped via tray icon
* Kill all unwanted threads with connection paused and re-use bandwidth polling thread for current session
* Uptime format
* Connected peers count is not displaying while launching the App
* No response while changing the Storage size
* Port is not forwarded response coming for the forwarded port during the initial check
* Unable to upload files using File Share
