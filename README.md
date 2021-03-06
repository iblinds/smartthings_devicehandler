# iBlinds SmartThings Device Handler

This is a device driver for iBlinds.  iBlinds is an intelligent Z-Wave blind motor that installs out of sight in existing Venetian (2" and 2 1/2" slatted-style) blind headrails. Use iblinds to tilt the slats open, closed or use the value slider for precise positioning of the slat tilt angle

<img src="http://myiblinds.com/icons/Screenshot_Android.png" width="200" height="350" />

## Installation

1. First pair your device with the hub (see the SmartThings manual for pairing instructions)
2. Open iBlinds_Demo4_DeviceHandler.groovy, select raw and it will open a new window with the code, select all (Ctrl+A) and copy the code (Ctrl+C)
3. Login to your SmartThings IDE at https://graph.api.smartthings.com (create a login if you don't have one AND don't forget to opt-in for the developer account). To verify that you're logged into the correct location, after logging into the above link, click on "My Locations" and then click on the name of the location where you want to install the SmartApp. Note: You may be asked to log into your account again when you click on your location, if so login again.
4. Click on "My Device Handlers"
5. Click on "+New Device Handler" on the top right 
6. Click "From Code"
7. Paste the .groovy code (Ctrl + V) into the editor and click "Create"
8. Click "Publish" and then "For me" on the top right 
9. Click on "My Devices" on the top
10. Click on your existing device (thermostat/lock etc which you want to change) 
11. Scroll down and click on "Edit"
12. Under "Type *" select the new device handler you just created (it will show up at the bottom of the list)
13. Scroll to the bottom of the page and click "Update"
14. Open the SmartThings App on your phone and under "My Home" look for your new device


## Credits

TODO: Write credits

## License


