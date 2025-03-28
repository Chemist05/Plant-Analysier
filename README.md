# Plant-Analysier
Hackathon project

## Inspiration
I have often seen in documentaries how farmers in arid region have problems with unpredictable weather conditions caused by climate change. The farmers who lived in a village irrigated their cornfields based on gut feeling - sometimes too much, sometimes too little. This gave me an idea. Using sensors to detect the problems earlier to prevent them and make farming more efficient.

## What it does
Sensors detect the temperature, humidity and soil moisture and show the sensor data to a dashboard.

## How I built it
First I built a circuit with:

1x ESP32
1x Breadboard 
1x DHT22 Sensor 
1x Yl-69 Soil Moisture Sensor and HC-38 Modul
8x Jumper Cables

Secondly, I connected the esp32 to the laptop using a micro usb cable and then uploaded the code. Then, in Arduino IoT Cloud, I linked the cloud variables I created with the variables in my code and connected to my Wi-Fi. Finally, I designed the dashboard and uploaded the code to ESP32.

## Challenges I ran into
Buy the components and find a right circuit designer for the project.

## Accomplishments that we're proud of
I am proud that my project works at all.

## What I learned
How to make a circuit and how to use circuit designer software. But also the problems caused by water shortages, heat waves, parasites, etc that farmers are faced with

## What's next for Plant Analyser
Buy a pH sensor, NPK sensor and other nutrient sensors to detect more abiotic factors so that we can better understand the state of plants and take advantage of it.

## How it works 
The soil moisture sensor measures soil moisture, while the DHT22 sensor measures temperature and humidity. The sensor data is then displayed in the Arduino IoT Cloud dashboard.
