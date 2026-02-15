# Earthquake Prediction Using Deep Learning

## Overview

Earthquakes are among the most unpredictable and destructive natural disasters. This project presents a hybrid earthquake prediction and early warning system that integrates Deep Learning and Fuzzy Logic to analyze multi-modal seismic and environmental data.

The system is designed to detect hidden pre-seismic patterns, reduce uncertainty in noisy sensor data, and convert predictions into actionable risk levels for early warning.

---

## Problem Statement

To design a deep learning–driven system that analyzes multi-modal seismic and environmental data to predict potential earthquake occurrences with improved accuracy and early warning capability.

---

## Objectives

- Develop a fuzzy logic–based preprocessing system to handle noise and uncertainty.
- Extract spatial-temporal features from heterogeneous datasets.
- Implement CNN, LSTM, and hybrid deep learning models.
- Convert model outputs into interpretable seismic risk levels.
- Design an Early Warning System (EWS) for alert dissemination.

---

## System Architecture

### 1. Data Sources
- Real-time seismic waveform data
- Plate movement data (GPS, InSAR)
- Geological data (fault stress, crust parameters)
- Remote sensing data (thermal, radar imagery)
- Historical earthquake records
- Environmental & atmospheric data

### 2. Fuzzy Preprocessing Layer
- Handles noisy and uncertain sensor readings
- Converts numerical inputs into fuzzy linguistic variables
- Applies membership functions
- Performs anomaly detection and sensor fusion

### 3. Feature Engineering
- Structured feature extraction
- Temporal pattern encoding
- Noise Index and Data Quality Index (DQI) computation
- Cleaned dataset generation

### 4. Deep Learning Model
- CNN for waveform classification
- LSTM/GRU for time-series forecasting
- Hybrid CNN-LSTM architecture
- Outputs:
  - Earthquake magnitude prediction
  - Probability score
  - Regional risk estimation

### 5. Fuzzy Decision Layer
- Converts numeric predictions into:
  - Low Risk
  - Moderate Risk
  - High Risk
- Improves interpretability and supports decision-making

### 6. Early Warning System (EWS)
- Generates alerts
- Supports real-time dissemination to authorities and applications

---

## Dataset

Primary dataset used for preprocessing and model validation:

**Air Quality Dataset (UCI Machine Learning Repository)**

Features include:
- CO(GT)
- NMHC(GT)
- C6H6(GT)
- NOx(GT)
- NO2(GT)
- Temperature (T)
- Relative Humidity (RH)
- Absolute Humidity (AH)

The dataset was used to demonstrate fuzzy-based cleaning, noise handling, and feature engineering techniques.

---

## Results

- Improved signal stability after fuzzy-based cleaning.
- Effective reduction of noise and uncertainty.
- Hybrid modeling shows potential in identifying pre-seismic patterns.
- Anomalies may appear prior to significant seismic events.
- Generalization remains a challenge due to complex earthquake dynamics.

---

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Fuzzy Logic Systems (Mamdani, Sugeno, ANFIS)
- Time-Series Analysis

---

## References

### Research Papers
- Akhoondzadeh & Marchetti (2022) – Multi-sensor fuzzy inference for earthquake prediction  
- Andalib et al. (2016) – Fuzzy expert system for Zagros fault zone  
- Upadhyaya & Dashore (2011) – Fuzzy logic-based AQI model  

### Resources
- UCI Machine Learning Repository – Air Quality Dataset  
- Andrew Ng – Deep Learning Specialization (Coursera)

---

## Future Work

- Integration with real-time seismic waveform datasets
- Deployment-ready Early Warning System
- Improved hybrid architectures
- Regional calibration for better generalization
- Large-scale validation with multi-sensor data

---

## Author

Shantanu Bakshi  
23FE10CSE00520  
School of Computer Science and Engineering  

Supervised by:  
Dr. Ankit Srivastava

---

## Project Status

Under progress.
