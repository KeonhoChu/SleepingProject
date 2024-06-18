# Sleeping_Pattern_Predict_Project
![표지](https://github.com/KeonhoChu/SleepingProject/blob/main/%EA%B7%B8%EB%A6%BC1.png?raw=true)
# Lite-Right: Personalized Wake-Up Time Prediction and Sleep Pattern Analysis

## Overview
Lite-Right is an innovative medical application designed to enhance the quality of sleep by predicting personalized wake-up times. The application leverages a hybrid LSTM-CNN model to analyze sleep patterns and integrates IoT devices to operate in conjunction with the user’s personalized wake-up time.
![플로우](https://github.com/KeonhoChu/SleepingProject/blob/main/%EA%B7%B8%EB%A6%BC3.png?raw=true)
## Key Features
1. **Personalized Wake-Up Time Prediction:** Using a sophisticated LSTM-CNN model, Lite-Right analyzes sleep patterns to predict the optimal wake-up time for each user.
2. **Sleep Stage Detection:** The application identifies and categorizes sleep stages into Awake, REM, Core, and Deep stages, based on the traditional sleep cycle of N1, N2, N3, N2, and REM.
3. **IoT Device Integration:** Seamless integration with IoT devices to enhance user experience and provide a holistic sleep management solution.
![비전](https://github.com/KeonhoChu/SleepingProject/blob/main/%EA%B7%B8%EB%A6%BC4.png?raw=true)
## Technical Specifications
- **Programming Languages:** Python, MySQL
- **Machine Learning Framework:** TensorFlow/Keras for developing the LSTM-CNN model
- **Web Interface:** Streamlit for developing the Polit Web
- **Mobile Application:** Swift, Xcode for developing the iOS application

## Sleep Cycle and Stages
The human sleep cycle is typically divided into the following stages:
- **N1 (Light Sleep):** Transition between wakefulness and sleep
- **N2 (Light Sleep):** Onset of sleep, heart rate slows, and body temperature drops
- **N3 (Deep Sleep):** The most restorative stage of sleep
- **REM (Rapid Eye Movement):** Stage associated with dreaming and memory consolidation

In Lite-Right, these stages are labeled as:
- **Awake**
- **REM**
- **Core (N1 and N2)**
- **Deep (N3)**

## Project Components

### LSTM-CNN Model
The core of Lite-Right’s functionality is the LSTM-CNN hybrid model which is responsible for:
- **Data Preprocessing:** Cleaning and normalizing raw sleep data from wearable devices.
- **Feature Extraction:** Identifying important features that influence sleep stages and wake-up times.
- **Training and Validation:** Using labeled sleep data to train the model and validate its accuracy in predicting wake-up times.

### IoT Device Integration
Lite-Right integrates with various IoT devices to monitor and enhance the user's sleep environment. This includes:
- **Smart Lights:** Adjusting light settings to simulate natural wake-up conditions.
- **Thermostats:** Regulating room temperature for optimal sleep conditions.
- **Wearable Devices:** Collecting real-time sleep data for continuous monitoring and analysis.

### Web and Mobile Application
#### Polit Web
Developed using Streamlit, the web interface allows users to:
- View and analyze their sleep patterns
- Access personalized sleep reports
- Manage connected IoT devices

#### Mobile Application
Developed using Swift and Xcode, the mobile app provides:
- Real-time sleep tracking and analysis
- Personalized wake-up time notifications
- Integration with wearable and IoT devices


![비즈니스](https://github.com/KeonhoChu/SleepingProject/blob/main/%EA%B7%B8%EB%A6%BC2.png?raw=true)






