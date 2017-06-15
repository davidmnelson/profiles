# Profiles
These are some of my mobileconfig profiles for Apple operating systems. 

## ChromeSecuritySettings.mobileconfig ##
Google Chrome: Disables form autofill, password viewing/saving, prevents changes to proxy settings, and blacklists all but a handful of Chrome extensions.

## NotificationCenterHideFortiClient.mobileconfig ## 
Sets default preference for all FortiClientAgent alerts to be hidden in Notification Center. Created because FortiClientAgent seems to alert users of phantom software updates multiple times a day.

## PrintFooterWithHardwareAddress.mobileconfig ##
Printing: Forces footer with username, date/time, and MAC address on all print jobs. Useful for tracking abuse/over-use of printers.

## SoftwareUpdateRestrictions.mobileconfig ##
Disables automatic updates for OS and apps, but updates for XProtect and configuration data remain active. Disables installation of prerelease software. Disables app adoption. 
