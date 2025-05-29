# temp-humidity-sensor-arduino
An Arduino-based temperature and humidity sensor using DHT11
# Weather Monitoring System using Arduino and DHT11

This project is a simple weather monitoring system built using an Arduino Uno and a DHT11 sensor. It reads the temperature and humidity of the surrounding environment and displays the data on the Serial Monitor in real-time. It's a basic yet practical example of sensor interfacing with Arduino, useful for beginners interested in embedded systems or IoT.

---

## What It Does

- Reads temperature (in °C) and humidity (%) using the DHT11 sensor
- Continuously displays the data on the Serial Monitor
- Updates every 2 seconds

---

## Components Used

- Arduino Uno
- DHT11 Temperature and Humidity Sensor
- Breadboard
- Jumper wires
- USB Cable (for power and serial communication)

---

## Circuit Setup

The DHT11 sensor is connected to the Arduino as follows:

- **VCC** → 5V
- **GND** → GND
- **Data** → Digital Pin (e.g., D2)

> *(Insert your own circuit image or a Fritzing diagram here)*

---

## How to Use

1. Connect the DHT11 to the Arduino according to the wiring above.
2. Upload the Arduino sketch (`dht11_weather_sensor.ino`) using the Arduino IDE.
3. Open the Serial Monitor (set baud rate to 9600).
4. Observe the live temperature and humidity readings.

---

## Demo

> *(You can replace this link with a Google Drive or YouTube video if you recorded one)*

![Output Example](output.jpg)

[Watch the project demo](https://drive.google.com/your-demo-video-link)

---





---

## About This Project

This was one of my early experiments with Arduino and sensors. It helped me understand how digital sensors work, how to handle serial data, and how to work with external libraries in the Arduino IDE. Simple projects like this are a great starting point before moving into more advanced embedded systems or IoT development.

---

## Author

**Your Name**  
B.Tech ECE, BIT Mesra  
[LinkedIn](https://linkedin.com/in/yourusername) | [GitHub](https://github.com/yourusername)


