# IoT-Data-Collection-Simulation
This project simulates an IoT device collecting sensor data from a motor and sending it to a cloud API. It's designed to demonstrate a realistic IoT data collection scenario with error handling, logging, and local data storage capabilities.
Features

Simulates multiple sensor readings (temperature, vibration, RPM, power)
Configurable via YAML file
Sends data to a cloud API (configurable URL)
Saves data locally if cloud upload fails
Implements logging for monitoring and debugging

Requirements

Python 3.7+
Required packages: requests, PyYAML

Setup

Clone this repository
Install required packages: pip install -r requirements.txt
Configure the config.yaml file with your desired settings
Run the script: python iot_data_collection.py

Configuration
Edit the config.yaml file to customize the simulation parameters, including sensor data ranges, collection intervals, and API endpoints.
License
This project is licensed under the MIT License - see the LICENSE file for details.
