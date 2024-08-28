# Weather_Station

<div align="left">

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/javascript/javascript-original.svg" height="50px" alt="JavaScript"  />


<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/html5/html5-original.svg" height="50px" alt="Html"  />
          

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/cplusplus/cplusplus-original.svg" height="50px" alt="C++" />  

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/arduino/arduino-original-wordmark.svg" height="50px" alt="Arduino" />  
    
</div>
          





## Overview
This project is a weather monitoring system built using the ESP32 microcontroller. 
It collects various environmental data such as `Temperature`, `Humidity`, `Heat Index` and displays the information in real-time.






## Description:
It is a Hardware & Software based project basically a IOT based project. 
It can be done using any type of hardware controller. Eg: `Arduino`, `ESP`, `Raspberry Pi`.
here we have used **ESP32** module 




## Why ESP32 ?
**ESP32** is a low cost microcontroller mostly used in IOT based project. It comes with built-in `WiFi` And `Bluetooth module` 
- **Connectivity**: ESP32 has built-in module 
  - Wi-Fi 
  - Bluetooth 
- **I/O port**:The microcontroller includes a variety of peripherals such as:
  - GPIO (General Purpose Input/Output) pins
  - ADC (Analog to Digital Converter)
  - DAC (Digital to Analog Converter)
  - PWM (Pulse Width Modulation)
- **Low Power Consumption**
- **Development Environments** : Arduino IDE





## Features
- **Real-time Data Monitoring**: Continuously measures and displays `Temperature`, `Humidity`, and `Heat Index`.
- **Database**: `ESP32` Sends data to a web server or here we have used `Google Sheets` as a database to store and retrieve historical data .
- **Interface**: Displays data on the website or a web dashboard. Data are being fetch from database (here `Google Sheets`).
- **Data Logging**: Stores historical data on database for `data analysis` and `data mining`.



# Project Requirements
## Hardware
- ESP32 
- Breadboard
- Wires
- AC to DC adaptor 
- **Sensors**
  - DHT11 (for `Temperature` `Humidity` `Heat Index`)
  - **Gas Director**
    - MQ7
    - MQ8
    - MQ135

## Software 
- Webpage 
- Google Sheets (Database)
- Google App console (retrieve data from ESP32)
- and a internet connection :)



# Arduino

> ``` C++
> #include<iostream>
> ```