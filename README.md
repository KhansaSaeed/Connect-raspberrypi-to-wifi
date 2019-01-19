# Connect-raspberrypi-to-wifi
Easiest and Cheapest way to  setup WiFi on Raspberry Pi 3 B+ without using  Monitor, Keyboard, Ethernet Cable &amp; Mouse.
Download the latest Raspbian image from this link: https://www.raspberrypi.org/downloads/raspbian/.
Download win32diskimager (https://sourceforge.net/projects/win32diskimager/) to copy image to SD card.
Once the image is installed in SD card then eject the SD card.
Insert again the SD card and a pop-up will ask you to format the SD card but just cancel that option.
Then unzip the folder of additional files provided in this repository.
Edit the wpa_supplicant.conf file. You have enter your wifi name and password.
Also go to this link (https://www.raspberrypi.org/documentation/configuration/wireless/wireless-cli.md) and modify the file according to your wifi settings.
i.e. whether you have a hidden network, network with no password or normal open network with password.
The given file is set for hidden wifi network.
After changings being done. Copy paste the two files (ssh and wpa_supplicant.conf) into the SD card in which the image was installed.
Then insert the SD card into Raspberry Pi.
Wait for few minutes.
In meanwhile install https://angryip.org/download/#windows.
Using angryIP scanner scan for devices connected to that WiFi.
You'll see raspberry Pi also given an IP Address. Note it down for future use.
Hurray! Now your Raspberry Pi 3 B+ is connected to WiFi :)
