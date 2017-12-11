TFT Display for Raspberry Pi 3
===============================

The Idea:
=========

I will work to make a touchscreen work with a raspberry pi 3. This project will let the user know His/Her position in line while he waits to get attention of a representative or an attendant.
Users can also lookup a product in store and once they are done shopping, they can fill out an E-Survey using a simple and interactive touch screen.

### December 11 2017

Placard:<br>
![Alt text](https://github.com/SaqibJaweed/Help-Line/blob/master/Publication2-1.jpg?raw=true "Placard")<br>

*30 Second Script*<br>
"Hello everyone, my name is Saqib Jaweed Syed and I am working on a 3.5’’ Touch Screen as my hardware project. The Idea behind this project is to accept input from the user without the use of mouse and keyboard at a help desk kiosk. The project costed me about $60 and required almost 8 hours of work altogether. I feel very accomplished at this point as I have now, got it to work with more functionality then promised. For e.g. Screen Mirroring and Remote access. I found that the screen is more responsive to a stylus as compared to using with finger due to its size. At this point though, I am anxiously waiting to couple it with Abhay’s PIR sensor and Guru’s RFID Reader next semester."

**0s-10s:** Unpacking and Assembling<br>
**11s-20s:** Powering on and Screen Mirroring<br>
**21s-25s:** Difference between Finger vs Stylus<br>
**26s-30s:** On-screen Keyboard Demo<br>


### December 04 2017
We had to fix a minor issue in the printed circuit board so the sensord could work correctly.
While Running the BME280.py code, I got the ImportError: No module named smbus but I was able to solve it by using the following command that installs the missing library.
```
sudo apt install python-smbus
```
<br>
The BME280 now reads and displays the humidity correctly.
![Alt text](https://github.com/SaqibJaweed/Help-Line/blob/master/Humidity.jpg?raw=true "Reading Humidity")<br><br><br>
Output of ghmain:<br>
![Alt text](https://github.com/SaqibJaweed/Help-Line/blob/master/T-L.jpg?raw=true "ReadingL&T")<br>
A picture of the back of my PCB Board to explain the changes I made to the original board.<br>
![Alt text](https://github.com/SaqibJaweed/Help-Line/blob/master/InkedPCB-fix.jpg?raw=true "PCB-fix")<br><br><br>

### December 03 2017
I had some time to kill today, so I tried to search of ways I can mirror my screen to another computer for remote access and also because writing code on a 3.5'' screen was very frustrating.

Guess what!!! I downloaded teamviewer on my personal laptop and my Raspberry Pi from [here](https://www.teamviewer.com/en/download/) and followed the instructions [here](https://community.teamviewer.com/t5/Knowledge-Base/How-to-install-TeamViewer-Host-for-Linux/ta-p/6318) to get things to work. It works like a charm without any lag. This means, that I can use my laptop's screen to use the Raspberry Pi. The only catch is that both the devices have to be on-line and due to security reasons, Terminal window can not be accessed through remote desktop and can only be accessed through the default display that is the 3.5'' TFT display.
### December 01 2017
I have tested the PCB board that I sodered and it works fine. I ran the traffic2B program and saw the LED is blinking in the pattern (OFF-GREEN-OFF-ORANGE-OFF) and also ran the ghmain program, that reads the light and temperature sensors. <br>
![Alt text](https://github.com/SaqibJaweed/Help-Line/blob/master/GreenLight.jpg?raw=true "Green Light")<br>
![Alt text](https://github.com/SaqibJaweed/Help-Line/blob/master/Reader1.jpg?raw=true "Output")<br>
![Alt text](https://github.com/SaqibJaweed/Help-Line/blob/master/Reader.jpg?raw=true "SenseHat Reader")<br>
![Alt text](https://github.com/SaqibJaweed/Help-Line/blob/master/SenseHat.jpg?raw=true "Sense Hat")<br>

My screen even works when I install it over the PCB board.
### November 28 2017
Got my PCB Board tested by Vlad at the Prototype lab. It works Perfect!!!
### November 20 2017
The Touch Screen is now displaying and taking inputs. The whole process to get it to work took almost 6 to 8 hours.



I used [this](https://learn.adafruit.com/adafruit-pitft-3-dot-5-touch-screen-for-raspberry-pi/easy-install) website for help and closely followed the steps.

Stay tuned for Videos, Pictures and Build instructions that are coming soon.
### November 10 2017
PCB Board made and sodered.
![Alt text](https://github.com/SaqibJaweed/Help-Line/blob/master/20171018_154102.jpg?raw=true "Completed PCB board")
![Alt text](https://github.com/SaqibJaweed/Help-Line/blob/master/20171018_153924.jpg?raw=true "Sodering in progress!!!")
### October 10, 2017
Hardware Parts bought from KIJIJI  
            1. Raspberry Pi 3 Module B Kit  $30.00 <br>
            2. 3.5'' Touch Screen Module by [adafruit.com](https://www.adafruit.com/product/2097)  $20.00 <br>
![Alt text](https://github.com/SaqibJaweed/Help-Line/blob/master/Capture1.PNG?raw=true "Screen Front View")
![Alt text](https://github.com/SaqibJaweed/Help-Line/blob/master/Capture.PNG?raw=true "Screen Rear View")
![Alt text](https://github.com/SaqibJaweed/Help-Line/blob/master/1-2.jpg?raw=true "Raspberry Pi 3 Model-B")
### October 02, 2017
Created [Budget](https://github.com/SaqibJaweed/Help-Line/blob/master/Budget.docx), to keep track on the project's affordability.
### September 25, 2017
Created [Gantt Chart](https://github.com/SaqibJaweed/Help-Line/blob/master/Gantt%20Chart.docx), that would help me to finish all tasks on defined time and stay on track.
### September 18, 2017
Created [proposal](https://github.com/SaqibJaweed/Help-Line/blob/master/ProposalContentStudentNameRev02.xlsx) for a 3.5'' TFT display. The display will be used as a default display for input and output.

## Author
* **Saqib Jaweed Syed** - [SaqibJaweed](https://github.com/SaqibJaweed)
