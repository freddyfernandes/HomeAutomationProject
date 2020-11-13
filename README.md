# HomeAutomationProject
Using tinkerCAD I have created a Home automation setup by simulating an Arduino connected to various sensors.
I have used lots of components including an Arduino Uno, gas sensor, PIR sensor, DC Motor, Relays etc.
The project is very simple to understand and use, when the switch is on, this indicates that the owners are home.
To indicate this, the bulb glows. Thw gas sensor works regardless of whether the owners are home or not.
I have set a base threshold value to the sensor. Any increase in the value registered by this sensor over the base value,
And the DC Motor starts spinning,replicating a ventilator fan, Also the RGB LED glows red.
When the switch is turned off, the bulb stops glowing. Then if the PIR sensor detects any motion withen its range,
The buzzer starts ringing, and the LED turns red again. This alarm system only turns off when the switch is turned back on.
Hope this project can be helpful to anyone that needs it. I have attached a .brd file of the project that can be directly uploaded.
