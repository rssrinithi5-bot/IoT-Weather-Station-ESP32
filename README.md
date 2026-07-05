# IoT-Weather-Station-ESP32
IoT-Weather-Station-ESP32 BEGINNER LEVEL
# IoT Weather Station - ESP32 + DHT22

Real-time temperature and humidity monitoring system that uploads sensor data to the cloud, with alert and power-saving features.

## Features
- WiFi connectivity (ESP32)
- DHT22 sensor for temperature & humidity
- Cloud data upload via ThingSpeak API
- LED alert system (triggers above 30°C)
- Deep sleep mode for power optimization
- WiFi auto-reconnect handling

## Hardware
- ESP32 Dev Board
- DHT22 Temperature & Humidity Sensor
- LED + 220Ω resistor
- 4.7kΩ pull-up resistor (DHT data line)

## How It Works
1. ESP32 connects to WiFi
2. Reads temperature & humidity from DHT22
3. Uploads data to ThingSpeak cloud dashboard
4. LED turns ON if temperature exceeds 30°C
5. Device enters deep sleep for 15 seconds to save power, then repeats

## Circuit Diagram
(screenshot here)

## Demo
(video link / screenshot here)

## Built With
Wokwi Simulator, Arduino C++, ThingSpeak
