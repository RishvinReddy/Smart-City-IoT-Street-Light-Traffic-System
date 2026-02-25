# Dashboard Architecture

## Sensor Data Flow
The dashboard begins with various sensors deployed throughout the smart city. These sensors gather data related to street light conditions, traffic flow, and environmental variables.

## Microcontroller Processing
All sensor data is sent to a microcontroller (e.g., Arduino or Raspberry Pi), which processes the information. The microcontroller filters, aggregates, and possibly preprocesses the data to reduce noise and send relevant information to manage the smart street lighting and traffic efficiently.

## WiFi Transmission
Once processed, the microcontroller transmits the data via WiFi to a designated cloud server. This transmission is real-time, ensuring that the dashboard reflects the most current conditions.

## Cloud Storage
The cloud storage solution captures incoming data, organizes it, and ensures it is available for retrieval. This storage can facilitate data analytics and machine learning applications, providing insights into traffic patterns and street light usage.

## Web Dashboard Visualization
Finally, a web dashboard visualizes the data in a user-friendly format. The dashboard displays real-time metrics, historical data trends, and analytics that help city officials and users understand the smart city's dynamics.

---  
**Note:** This architecture supports scalability to accommodate additional sensors and extended functionalities as needed.