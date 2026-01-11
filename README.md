# Nepal Earthquake Seismicity Prediction using Machine Learning

This project implements a **supervised machine learning model** to analyze and predict **earthquake magnitude in Nepal** using historical seismic data.  
The model is built using the **Random Forest Regression algorithm** and focuses on spatial and temporal seismic features.

# Project Overview

Nepal lies in a high seismic risk zone due to the collision of the Indian and Eurasian tectonic plates.  
This project aims to:
- Analyze earthquake seismicity patterns
- Predict earthquake magnitude using machine learning
- Identify important factors influencing seismic activity

# Model Details

- **Model Type:** Supervised Machine Learning  
- **Algorithm:** Random Forest Regression  
- **Prediction Target:** Earthquake Magnitude (Continuous Value)

# Features Used

- Latitude  
- Longitude  
- Depth  
- Year  
- Month  

Temporal features are extracted from the earthquake timestamp to enhance prediction performance.

# Dataset

- Historical earthquake data (CSV format)
- Includes:
  - Latitude
  - Longitude
  - Depth
  - Magnitude
  - Time
- Dataset can be obtained from sources such as **USGS Earthquake Catalog**

# Technologies & Libraries

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  

# How to Run the Project

# Clone the Repository
```bash
git clone https://github.com/your-username/Nepal-Earthquake-Seismicity-ML.git
cd Nepal-Earthquake-Seismicity-ML
