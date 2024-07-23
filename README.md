Working:-

The IoT-based health monitoring system utilizes an Arduino Uno microcontroller interfaced with a pulse sensor and an LM35 temperature sensor. The Arduino continuously collects data from these sensors. The pulse sensor measures heart rate, while the LM35 sensor monitors body temperature. This data is then processed and transmitted to the ThingSpeak cloud platform through the internet using ThingSpeak's API.

ThingSpeak allows users to create channels to store and visualize data in real-time. With the received data, users can monitor health parameters remotely through a web interface. Additionally, ThingSpeak offers analytical tools to detect trends and anomalies in the data. Users can set up alerts based on predefined thresholds, enabling timely notifications for abnormal health conditions.
