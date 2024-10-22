# 🏢VAST Challenge 2016: Analyzing GASTech Building Operations Data

This project, completed as part of the **VAST Challenge 2016**, focuses on analyzing operational data from the GASTech building. The data includes employee movements, HVAC sensor readings, and environmental parameters such as CO2 and Hazium gas levels. The goal of the project is to identify patterns, detect anomalies, and understand causal relationships between employee behavior and building conditions.

---

## 🌟 Project Features
- **Proximity Card Data Analysis**: Visualizing employee movement patterns using prox card data to detect anomalies and observe typical behaviors.
- **HVAC Sensor Data Analysis**: Investigating building sensor data such as temperature, energy consumption, and air quality measurements.
- **Anomaly Detection**: Identifying unusual patterns like irregular access card usage and CO2 spikes, which could indicate operational inefficiencies or security risks.
- **Causal Relationship Analysis**: Establishing links between anomalies in the building's data and employee behavior, with a focus on environmental conditions affecting operations.

---

## 🛠️ Tools & Technologies
| Tool/Technology  | Description  |
| ---------------- | ------------ |
| ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) | Python was used for data processing, analysis, and visualization. |
| ![Jupyter](https://img.shields.io/badge/-Jupyter-orange?logo=jupyter&logoColor=white) | Interactive environment for running the data analysis. |
| ![Pandas](https://img.shields.io/badge/-Pandas-150458?logo=pandas&logoColor=white) | Data manipulation and cleaning for proximity and sensor datasets. |
| ![Matplotlib](https://img.shields.io/badge/-Matplotlib-000000?logo=matplotlib&logoColor=white) | Visualization library for creating data plots. |
| ![Seaborn](https://img.shields.io/badge/-Seaborn-2E78D7?logo=seaborn&logoColor=white) | Advanced visualization library for drawing correlations and trends. |
| ![EnergyPlus](https://img.shields.io/badge/-EnergyPlus-5582a0?logo=energy&logoColor=white) | EnergyPlus for generating operational data and building simulations. |

---

## 📊 Key Visualizations
1. **Employee Movement Patterns**: Generated plots that show employee entry and exit times using proximity card data. These visualizations highlight anomalies, such as unusual card entries during non-working hours, indicating suspicious activities.
   
2. **HVAC and CO2 Data**: Time series plots of HVAC sensor data (temperature, energy usage, etc.) and CO2 levels. Specific days show abnormal peaks, particularly in CO2 levels, which could indicate operational inefficiencies or environmental issues.

3. **Hazium Gas Readings**: Visualization of Hazium gas concentrations across different floors, identifying hazardous events, particularly on the third floor where construction activities occur.

---

## 📋 Dataset Information
- **Proximity Card Data**: Employee movements were tracked via proximity card sensors throughout the building’s zones.
- **HVAC Sensor Data**: Environmental data such as temperature, CO2, and Hazium gas levels.
- **Building Layout**: Information on HVAC and proximity card zones, along with employee office assignments and roles.

---

## 🔮 Future Scope
- Machine Learning for HVAC Optimization: Implement machine learning algorithms to optimize the HVAC system for energy efficiency and comfort.
- Sensor Network Expansion: Expand the sensor network with additional environmental sensors for detecting hazardous gases, increasing the safety and efficiency of the building.
- Association Rule Mining: Use association rule mining techniques to uncover complex relationships between sensor data and building operations, predicting potential issues before they arise.
- Real-Time Data Integration: Explore real-time monitoring and anomaly detection to respond dynamically to operational inefficiencies and security threats.
