# Industry-Smart-Energy-Monitor-with-IOT
We have presented an Internet of Things based smart energy meter that can be deployed in households and industries to measure power consumption at the device level without disrupting the operation of the appliances and without the need for rewiring
The performance of the system has been tested using a variety of appliances and the accuracy has been validated by comparing it with the already known power rating of the appliance. The performance was evaluated using many household appliances from the categories mentioned previously.
The number of household appliances has drastically increased in the recent years and with this, so has the consumption and demand for electricity. In the face of declining energy resources, there is a need for a solution that can help track, measure and control the consumption of electricity. Conventional energy meters do not provide information regarding power consumption at the device-level, due to which consumers cannot monitor or log the electricity consumed by each appliance. To bridge the gap in device energy consumption data, we propose the design and implementation of an Internet of Things (IoT) enabled, minimalistic, cost-effective and efficient smart energy meter which will aid consumers in obtaining information on the energy consumption of any electrical appliance. This will not only assist consumers in ensuring that their devices function as per the energy rating but also help them access energy expenditure patterns formed over time which will contribute towards awareness and conscious conservation of energy.

## How to operate: 
## step 1: Scan the QR code and a link will be displayed
## step 2: Given link will open a graphical output 
## step 3: Power and time sample will be stored cloud network
## step 4: Real time data Consumption of power on per device is displayed on cloud


## Hardware
* NodeMcu ESP8266
* 5V USB Adaptor 
* 220V Bulb Holder with wire connector 
* Lamp Bulb 
* Single-Phase 5A Range AC Current Sensor
* Micro Usb cable 
* JUMPER wires (female - female )

## AC Current sensor 
* This single-phase current sensor module can measure AC currents up 5A. The sensitivity of the analog output can be adjusted using the on-board potentiometer.
* The module can measure AC currents less than 5A, the corresponding analog output 5A/5mA Rated Input Current: 5A Rated output current: 5mA On-board micro precision current transformer Onboard sampling strength
* PCB size: 18.3 x17 (mm) Change: 1000: 1 Linear range: 0 ~ 10A (100 ohms) Linearity: 0.2% Precision: 0.2
* Uses Insulation Voltage: 3000 V Measure Sealing material: epoxy resin Operating temperature: -40 °~ + 70 °

# What is thingspeak?
ThingSpeak is IoT Cloud platform where you can send sensor data to the cloud. You can also analyze and visualize your data with MATLAB or other software, including making your own applications.
The ThingSpeak service is operated by MathWorks. In order to sign up for ThingSpeak, you must create a new MathWorks Account or log in to your existing MathWorks Account.
ThingSpeak is free for small non-commercial projects.
ThingSpeak includes a Web Service (REST API) that lets you collect and store sensor data in the cloud and develop Internet of Things applications. It works with Arduino, Raspberry Pi and MATLAB (premade libraries and APIs exists) But it should work with all kind of Programming Languages, since it uses a REST API and HTTP.
## ThingSpeak Communication Library for Arduino, ESP8266 and ESP32
This library enables an Arduino or other compatible hardware to write or read data to or from ThingSpeak, an open data platform for the Internet of Things with MATLAB analytics and visualization.
Hardware specific examples are found here. But to give you an idea of usage examples for writing and reading with an ESP8266 are shown below. Complete documentation in also shown below.

ThingSpeak offers free data storage and analysis of time-stamped numeric or alphanumeric data. Users can access ThingSpeak by visiting http://thingspeak.com and creating a ThingSpeak user account.

ThingSpeak stores data in channels. Channels support an unlimited number of timestamped observations (think of these as rows in a spreadsheet). Each channel has up to 8 fields (think of these as columns in a speadsheet). Check out this video for an overview.

Channels may be public, where anyone can see the data, or private, where only the owner and select users can read the data. Each channel has an associated Write API Key that is used to control who can write to a channel. In addition, private channels have one or more Read API Keys to control who can read from private channel. An API Key is not required to read from public channels. Each channel can have up to 8 fields. One field is created by default.

You can visualize and do online analytics of your data on ThingSpeak using the built in version of MATLAB, or use the desktop version of MATLAB to get deeper historical insight. 
Visit https://thingspeak.com/channels/1394956

Libraries and examples for Arduino devices can be found here: https://github.com/mathworks/thingspeak-arduino
## Installation
In the Arduino IDE, choose Sketch/Include Library/Manage Libraries. Click the ThingSpeak Library from the list, and click the Install button.
--- or ---
Download the ZIP file (below) to your machine.
In the Arduino IDE, choose Sketch/Include Library/Add Zip Library
Navigate to the ZIP file, and click Open

## Methods
* Single-Phase 5A Range AC Current Sensor should connect with Analog Pins of NodeMCU 
* Setup the probe with human body and connect with nodemuc with 5v power supply
* A light Blub will get activate on AC power supply and Output will be shown in the graphical format of power and time 
* SCAN  or visit the link in which thingspeak cloud graph has been displayed 
## Refernce
* https://thingspeak.com/
* https://www.analog.com/media/en/technical-documentation/data-sheets/ad8232.pdf
