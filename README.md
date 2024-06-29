# TSA-project

# Pump sensor data Anomaly detection
The dataset consists of sensor data collected from various sensors monitoring a water pump system in a rural area. This data is critical for understanding the operational status of the system and predicting potential failures before they occur. The goal is to leverage this dataset to develop predictive models that can anticipate system failures and prevent disruptions that affect the community.


Dataset Link: https://www.kaggle.com/datasets/nphantawee/pump-sensor-data

### Content:

The dataset is organized into three main groups:

- Timestamp Data: Records the date and time of each observation.

- Sensor Data (52 Series): Includes raw sensor readings from 52 different sensors deployed within the water pump system. These sensors capture a variety of operational parameters such as temperature, pressure, flow rate, and electrical readings. Each sensor provides a continuous stream of data over time, allowing for detailed analysis of system behavior.

- Machine Status: This is the target label indicating the operational status of the water pump system at each timestamp. It categorizes each observation into one of the following classes:

            NORMAL: Indicates normal operation without any issues.
            RECOVERING: Indicates a temporary recovery phase after a previous failure.
            BROKEN: Indicates a system failure that requires immediate attention and repair.


### Acknowledgements:

The dataset is provided by a team responsible for managing the water pump system. It was shared to facilitate the analysis and improvement of predictive maintenance strategies to minimize downtime and prevent disruptions that impact the community's daily life.
