# Smart Chef

Smart Chef is a new concept product which aims at encouraging people to cook for themselves. The system is consists in a hardware device connected to a smartphone running a game app. Here we present the hypothetical features as well as the first prototype.

## Motivations

Cooking is healthy, culturally rewarding, and above all funny. Yet, many people don't cook and have never learnt how to, either because it is not part of their culture and they never had the opportunity to, or because they simply don't have time for it.
As a team of cooking-lover engineers attending the Singapore Nanyang Technopreneurship Center *Startathon*, we decided to tackle this problem by developping an inovative and affordable solution: Smart Chef.

## Concept

A smartphone app guides the user through several recipes, coming from different parts of the world and having diverse levels of difficulty. Step by step, the user receives feedback about his or her cooking technique in a fun and interactive way, allowing him or her to quickly be able to cook delicious food.

A small device is attached to the cooking pan or pot, and measures several parameters related to the food being cooked, such as temperature, CO2, or vibrations. This data is sent over Bluetooth to the smartphone, which analyses them, and convert them into an intuitive feedback. The device is removable and discreet, so it does not bother the user.

<img align=“center” src="doc/Technical_slide.jpg" width=“250”>

## Hardware Device

Main features:
* Three sensors measuring temperature, CO2 concentration, and acceleration
* Status LEDs
* Battery powered
* Optimized power consumption: BLE communication, low-power microcontroller, carefully selected sensors...

Early prototype:
* Arduino UNO
* Dallas DS18B20 thermocouple 
* InvenSense MPU-6050 IMU
* Bluetooth HC-05 module
* Green, Orange and Red LEDs controlled by the smartphone

## Smartphone App

<img align=“center” src="doc/app_ui.png" width=“250”>

[Link](https://play.google.com/store/apps/details?id=com.SevaneGames.SmartChef)

## Awards

This project won the thrid place of the Singapore Nanyang Technopreneurship Center *Startathon*, a 32-hour event focusing on idea development and implementation.

## Credits

* Software development: Alexis Pomares Pastor and Timoté Vaucher
* Hardware and firmware development: Paul-Edouard Sarlin
* Prototype design: Ignacio Albert Smet
* Business plan and speech: Jacques Weniger
