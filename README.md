# SmartBot: Real-Time Gas Monitoring and Anomaly Detection in Petroleum Industry Using IoT and Machine Learning
SmartBot, a remote-controlled car, operated via the Blynk IoT app, is equipped with MQ-2, MQ-3, and MQ-135 sensors for real-time environmental data collection. Continuously transmitting data to Google Sheets, SmartBot utilizes the One Class SVM model for anomaly detection, ensuring early identification of irregularities in various environments. 

## Components
1. Raspberry Pi PIco W : The Raspberry Pi Pico W is utilized for transmitting sensor data to Google Sheets via webhooks.
2. ESP8266: The ESP8266 serves as the control unit for SmartBot, allowing it to be remotely controlled via the Blynk IoT app.
3. MQ Sensors: SmartBot is equipped with a range of gas sensors, including the MQ-2, MQ-3, and MQ-135. These sensors detect various gases present in the environment, providing crucial data for monitoring air quality and detecting potential hazards.
4. L298N Motor Driver: The L298N motor driver controls the movement of SmartBot's motors.

## Circuit Diagram 
1. Raspberry Pi Pico W and MQ-sensors
 ![WhatsApp Image 2024-04-08 at 11 25 43 PM (1)](https://github.com/bachewar-bhushan/SmartBot/assets/142074907/fecacc1b-fa01-4436-8969-2afc7731bb63)

2. ESP8266 and L298N Motor Driver
   ![image](https://github.com/bachewar-bhushan/SmartBot/assets/142074907/1e939ce1-ca5a-4ee6-86a3-70f5dd9ecce0)
