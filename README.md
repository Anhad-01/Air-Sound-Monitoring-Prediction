# Air-Sound-Monitoring-Prediction
An IoT and ML-based system for real-time air and sound pollution monitoring and prediction.

The project combines **IoT and Machine Learning** to track environmental pollution in real time. Using an **ESP32 microcontroller**, the system collects data from **MQ-135 (gas sensor), LM393 (sound sensor), and DHT11 (temperature and humidity sensor)**. The collected data is sent to **ThingSpeak**, where it is stored and visualized for further analysis. This IoT-based approach enables continuous monitoring of air quality and noise levels, providing real-time insights into environmental conditions.  

To analyze and predict pollution trends, **Machine Learning models** were applied to the collected data. **K-Means Clustering** was used to categorize pollution levels, identifying patterns and correlations among environmental parameters. **LSTM** networks were trained to predict future temperature, humidity, gas concentration, and sound levels based on historical data. These predictive capabilities make the system valuable for proactive pollution management, allowing authorities to anticipate changes and take necessary actions.
