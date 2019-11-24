# ArduinoJson5
A simple install resource for ArduinoJson 5 that enables you to run alongside ArduinoJson 6... 

If you have Arduino Json installed it is likely version 6, and you have a sketch complaining about needing version 5, and you don't have eithe rthe skill or the inclination to pull it across. 

However, there is a work around, while still having Arduino Json 6 installed.

All of this is from the Arduino Json v5 site. 
Any linking is for convenience purposes and no code changes are intended or made to the ArduinoJson-v5.xx.x.h file. 
The original source https://arduinojson.org/v5/doc/installation/ 
(i.e. you could achieve the same thing with a download and manual GUI folder placement)

To execute, from your terminal client of choice:

cd into you sketchbook libraries folder.

From there:
  $ git clone https://github.com/JHale716/ArduinoJson5.git ArduinoJson-v5.13.5

This will place the repo and the ArduinoJson-v5.13.5.h file for ArduinoJson5 into this folder.

In your sketch, substitute ArduinoJson.h for ArduinoJson-v5.13.5.h and you'll be good to go!

Simple and effective.
