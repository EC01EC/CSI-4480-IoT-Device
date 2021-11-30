# CSI-4480-IoT-Device
CSI 4480 - Fall 2021 Oakland University
Developed by Martin Hughes, Reed Sikorski, Y Duong, and Eric Chan

A script to link a Raspberry Pi with an Arduino connected DHT11 sensor connected to the Kaa Open-Source IoT platform.

The code in the file "kaaconection.py" has to be modified with the information kaa provides you on account setup. DON'T LOSE THAT INFORMATION!

Set up your Raspberry Pi similar to the image below and look at the pin you are plugged into and make sure the pin in the code is set to the same pin the senor is plugged into on the Arduino!

![Capture](https://user-images.githubusercontent.com/60445081/144125723-61af448d-efb9-4274-8f15-ed3a1010cd87.PNG)

Put the code in a folder on the pi and install the following and place the extracted folders in the folder with your code. 
https://www.arduino.cc/reference/en/libraries/tinydht-sensor-library/
https://www.arduino.cc/reference/en/libraries/arduinomqtt/

Or install paho and adafruit via command line on the pi. If you try to run the code without these directorys installed, it will not work and will prompt you to do so.

Enjoy!
