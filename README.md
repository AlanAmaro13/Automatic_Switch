# Project: Automatic Switch for a Bedroom

In the following note, I describe the design and building process for an automatic
switch. This means a switch with the capability to synchronize with Google, Alexa, and
other virtual assistants. I also include a YT playlist with main demostrations.

Pictures:
![Principal](https://github.com/AlanAmaro13/Automatic_Switch/blob/main/Imagenes/1.jpeg)
![Frontal](https://github.com/AlanAmaro13/Automatic_Switch/blob/main/Imagenes/Frontal.jpeg)

## Table of Contents

- [Material](#material)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Material
The components needed to recreate this project are:

1) ESP32 C3 Super mini
2) Relay Module 4 Channels 5V
3) Voltage Regulator AC-DC 5V 2A (you can also use 1A)
4) 4 resistors 220 ohms
5) 4 switches
6) A Type C - Cable

Optional:
1) A circuit board pre-soldered
2) A lot of cable (for electronic and electric connections, gauge of your preference)

## Installation
In the documents, you will find the main code. It's important to have logged into
SinricPro, so all your devices can synchronize with the switch. The main code
requires the WiFi name and key.

It also requires the SinricPro key to use it correctly. By adding the
devices into your SinricPro account, the page will give you the code for the ESP32.
So the main code is just for reference of what you should get.

The construction of the device is done as follows using the diagram of connections:
First, I soldered the ESP32 to the pre-soldered board using female headers. I made
the connections between the microcontroller and the relay module using dupont cable.

Next, I soldered the switches to the board. It's fundamental to add the resistors
to the pin designated for receiving the switches signals to ground. While developing
this project, I had to deal with interference caused by not adding resistors.
So, you really should add them.

This optional step is to solder all the pins of the relay modules to the AC connectors.
I've done this step because I prefer these new connections, and it's also easier to connect
all your lights to it.

Finally, I soldered the Type C cable to the voltage regulator and added an AC Input.

Note: Depending on the electric power of the devices you're going to connect, you must
consider what gauge of cable you're going to use. In this case, I used a very tiny cable
because I only connect two LED lights to it.

## Usage
In the SinricPro page, you'll be able to turn on and off all the lights. I recommend you 
synchronize with Google Home, so you don't need to log in the page every time you want to 
turn on a light. Also, with Home, you can program routines, and the lights will turn off at
determined times you decide.

I've also done a series of videos showing its main funcionating in:

Google Home:
https://youtu.be/XFvWho0PaZE 

Virtual Assitance:
https://youtu.be/HTCfevFzbOc 

Switches:
https://youtu.be/oVQGTzcmvcI 


## Contributing
Finally, I'd like to say thank you to all the people who have believed in my projects.
It's because of you that today this project is done. So, thank you so much. I wouldn't be here if you weren't there.

## License
Licencia Creative Commons Attribution-NonCommercial-ShareAlike (CC BY-NC-SA)
