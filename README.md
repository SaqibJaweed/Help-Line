###Hardware Build Guide
This page describes the build process for 3.5`` Raspberry Pi 3 Model B touch screen, but the process is the same for any model starting from Raspberry Pi 2.
![Alt text](https://github.com/SaqibJaweed/Help-Line/blob/master/final_product.jpg?raw=true "final_product")
<br>
##Step 0: Read these Instructions
Seriously. There are probably things in these later steps that you should know about before getting started.
<br>
##Step 1: Order the Parts
The good thing about this project is that you only need to order a few things that you can also order from any website even different from the ones mentioned below for a cheaper price. 

1.	One Raspberry Pi 3 Model B from https://www.canakit.com/raspberry-pi-3-model-b.html?cid=cad&src=raspberrypi for CA$45.95

2.	One PiTFT - Assembled 480x320 3.5" TFT + Touchscreen for Raspberry Pi from
https://www.adafruit.com/product/2097

QTY	DISCOUNT
1-9	CA$44.95
10-99	CA$40.46
100+	CA$35.96

3.	One 16GB – 32GB class 10 Micro SD card from https://www.amazon.com/SanDisk-Ultra-Micro-Adapter-SDSQUNC-016G-GN6MA/dp/B010Q57SEE/ref=sr_1_6?s=pc&ie=UTF8&qid=1516559163&sr=1-6&keywords=micro+sd for CA$9.98

4.	Universal power supply from https://thepihut.com/collections/raspberry-pi-accessories/products/official-raspberry-pi-universal-power-supply for CA$12 .00

All the above materials will cost you Approx. CA$112.00 
<br>
##Step 2: Time Commitment
If you have decided to work on this project, make sure you give yourself enough time for all parts to arrive that can take upto 2 weeks to arrive unless you pay extra for fast delivery. But it does not ends here, even when the parts arrive, it will take atleast 2 hours of work to make the project from start to finish. Be careful to work in a neat and non-conductive environment, handling the touch screen with care and delicacy at all times.
<br>
##Step 3: Pre Install, SD Card Prep.
These instructions will prepare you for the later steps and contain instruction on how to install the Raspbian image on the SD card.
1.	Insert your microSD card into your card reader and find out its drive letter in Windows Explorer (for example G:).
2.	Format the card in FAT32 format.
3.	Download Win32DiskImager from https://sourceforge.net/projects/win32diskimager/  unzip the downloaded file and run the utility file.
4.	Download the Latest Jessie image that contains the requires TFT display drivers from https://drive.google.com/file/d/1LjGL4q_rgiJxwAZnhUNQZa28Kp7b6usB/view 
5.	Select the Raspbian image file you downloaded.
6.	Select the drive of your SD card in the ‘Device’ dropdown. Make sure you chose the correct one. Otherwise, you risk damaging the data on your hard drive.
7.	Select ‘Write’ and wait for the process to finish which may take around 20 minutes to complete. That’s it!
<br>
##Step 4: Mechanical Assembly
The whole process of this project’s assembly is relatively easy if you follow the following insructions carefully:
1.	Place the Pi on a non-conductive surface with GPIO pins facing up
2.	Place the female pins of the screen onto the pins of the Raspberry Pi, aligning them to the left most pins and then press firmly to make the pins go all the way in the adapter to make sure there are no loose parts. 
3.	Insert the SD card in the SD card slot carefully with the specified Raspbian image in it.
4.	Connect the power supply cable to the Raspberry Pi and let it sit for 2 minutes for the first time and the display will turn on and start recognizing inputs.
5.	As the screen is small, it is recommended to use it with a stylus.
<br>
##Step 4.1: Extras
This part of the build instruction is only to be followed if you want to install your project in a 3D printed case:
1.	Download the files from
2.	Send the files for 3D printing that will come out in 3 parts and will need a minimum of 4 hours to complete
3.	You will need 12 2.5mm Allen head bolts 6-10mm long
4.	Remove the SD card from the Raspberry Pi and install it in the middle printed part with 4 2.5mm Allen head bolts 6-10mm long as shown:
5.	Break the mounting tabs from all 4 sides of the screen as follows and the install the screen on the Pi carefully and re-insert the SD card in the slot carefully.
![Alt text](https://github.com/SaqibJaweed/Help-Line/blob/master/tab_break.jpg?raw=true "tab_break")
6.	Arrange the pieces as shown below:
![Alt text](https://github.com/SaqibJaweed/Help-Line/blob/master/pi_install.jpg?raw=true "pi_install")
![Alt text](https://github.com/SaqibJaweed/Help-Line/blob/master/screen_install.jpg?raw=true "screen_install")
7.	Fix the parts together with 8 2.5mm Allen head bolts 6-10mm but do not tighten too much as it might snap the plastic
8.	That is it! All ports and screen should now be usable with Raspberry Pi and Screen sitting on a 45 degree angle from our face, secured in a case.
<br>
##Unit Testing
The Project looks absolutely stunning and makes it easy for the users to interact with the Pi using the touch screen. Since I printed the plug Friendly version of my case, the ports stick out of the case by 2mm so that it is easily compatible with every kind of input/output cable.
<br>
##Production Testing
With the .img file available in hand, we can avoid the hassle of downloading the display drivers through the Raspberry Pi which takes 4 hours, fails often and needs an active internet connection throughout the process.
Considering if we have the files and software downloaded, we only need 30 minutes to reproduce the project. Imagine the speed in a case where you are producing 50 touchscreen computers in just over 24 hours.
