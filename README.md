
#### July 2020 (version 1.0.0)

Here are the highlights:

* **Size**: 
   windows - 84.6 MB
   linux - 74.4 MB
   mac -  114.5 MB
* **Date**: 13 July 2020

**Improvements**

* Software Auto update feature added in windows os
* Port Forwarding
* App Size Reduced
* Send OTP on sms
* Refer friend functionality
* GRPC event integration (polling is removed and any event will trigger then it will catch the event and reflect like token, balance)
* Storage size validation (if you utilize your storage and then try to reduce size then it will message)
* Tooltip information containing name streamsapce
* Uptime percentage is sync with cli
* Rebranding change
    Cacher Desktop Application-streamspace => Hive Desktop app - SWRM Labs
    SSH => SWRM
    Streamspace => SWRM Labs
    Cacher => Hiver
    Icon changes
* Download Queue issue resolve when storage is not available
* Upload Queue issue resolve when storage is not available
* After loading login will not come if user is already logged in

**UI FIXES**
1. whiteheader icon left margin
2. dashboard font dynamic size
3. node page equal card height
4. wallet paage increase card height
5. wallet font dynamic
6. earning font dynamic
7. earning graph height
8. earning alignment down
9. logo in earning page
10. band width over time small screen alignment issue
11. All index.html cdn link should made as local assets (except cdn icons)
12. software update modal size , font style , software update at center
13. refer friend modal input field , position
14. fileshare dragfiles height , space between icon and text retrive file button
15. file hash input field not correct
16. close icon in modals
17. New Logo Added (HIVE)

These are the improvement we have done

**Bug Fixes**

* Cli event integration with desktop application- CDN 770
* Confirmation required before deleting a File - CDN 741
* UI issues in desktop app - CDN 740
* Refer friend functionality -CDN 696
* When ping url of software-update not found - CDN 676
* Upload queue allows duplicate file entries (intermittent) - CDN 769
* Upload stuck at 0% if the file is uploaded when daemon is not running - CDN 595
* Timer is displaying with grammatical errors -CDN 889
* Another tab in task bar to show the status of connection. 
* Resizing of fixed width in windows causing issue. 
* Working on Earnings page calculation by uploading files to Customer. 
* Intermittent behaviour of Timer stuck at 00:00:00 
* Killing all the process after stoping daemon successfully from app
* Added daemon check to add file
* Added loader while pausing
* adding loader while pausing from tray
* Start & Stop are dependent on Timer. 
* Killing PID after stopping daemon from tray icon
* Kill all unwanted threads while pause connection and re-use bandwidth polling thread for current session
* Uptime timer when its greater then 24 hrs
* Multiple upload file


These are the closed bugs

#### Thank You
