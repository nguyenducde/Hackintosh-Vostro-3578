# Hackintosh-Vostro-3578 EFI
## Configuration Laptop

| Device | Name|
|--------------|-------|
| CPU | I7-8550U| 
| Wireless |AC 3165 | 
| Graphics card| UHD 620&&Radeon 520| 
| Sound card| ALC 236| 
| Ram| 8gb bus 2400 ddr4| 



Not working:
Wireless, Radeon 520


### Fix TrackPad not found 

Step 1:Open the terminal and type the command **sudo mount -uw /** then enter the password.

Step 2:Dowload install trackpad https://izicloud-my.sharepoint.com/:f:/p/ducde678/Esh87zyUm39BjwVfdtpXhLcBJoDKyVtbXu9BM5sNVTef-g?e=OT6IKY

Step 3:Click install.sh in file Install TrackPad

Step 4:Open the terminal type the command **sudo cp -r path Trackpad.prefPane in file Install TrackPad   /System/Library/PreferencePanes**

For example: **sudo cp -r /Users/nguyenducde/Desktop/Trackpad.prefPane /System/Library/PreferencePanes**

Step 5:Open the terminal type the command **sudo kextcache -i/**

Step 6 :Restart 

<img src="https://i.imgur.com/id4JsRJ.png">
<img src="https://i.imgur.com/gBT1V1i.png"> 
<img src="https://i.imgur.com/QBAS2LX.png">



