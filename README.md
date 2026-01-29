# Nepal Earthquake Trend Analysis and Seismic Risk Prediction Based on Severity Classification

## Overview
This project analyzes historical earthquake data of Nepal to understand long-term seismic trends and applies machine learning techniques to classify earthquake severity and estimate seismic risk levels.

Using earthquake records from the USGS catalog (1900–2026) and NEMRC catalog (1994-2025), the project combines exploratory data analysis, geospatial visualization, and supervised machine learning to identify seismic patterns and support data-driven risk assessment.

The project focuses on **risk estimation and pattern analysis**, not exact earthquake prediction.

---

## Objectives
- Analyze long-term earthquake trends in Nepal.
- Study spatial distribution of earthquakes.
- Classify earthquakes based on severity levels.
- Use classification results to estimate seismic risk.
- Visualize earthquake distribution using geospatial tools.

---

## Dataset
- **Source:** United States Geological Survey (USGS) & National Earthquake Monitoring and Research Center (NEMRC)
- **Region:** Nepal and surrounding areas
- **Time Range:** 1900 – 2026
- **Typical Features:**
  - Date and time
  - Latitude
  - Longitude
  - Depth
  - Magnitude
  - Location description

---

## Project Components

### 1. Trend Analysis (EDA)
- Earthquake frequency over time
- Magnitude distribution analysis
- Depth vs magnitude relationships
- Pre and post major earthquake comparisons

### 2. Geospatial Visualization
- Earthquake distribution maps
- Severity-based mapping
- Regional seismic concentration analysis

### 3. Machine Learning Model
A supervised learning model is used to classify earthquake severity.

Example severity classes:
- Low Severity
- Moderate Severity
- High Severity

Models evaluated may include:
- Logistic Regression
- Decision Tree
- Random Forest

### 4. Seismic Risk Estimation
Risk levels are derived from severity and frequency patterns to identify relatively high-risk regions or periods.

---

## Tools & Technologies
- Python
- Pandas & NumPy
- Matplotlib
- GeoPandas
- Scikit-learn
- Jupyter Notebook

---

## Project Workflow
1. Data collection
2. Data cleaning and preprocessing
3. Exploratory data analysis
4. Feature engineering
5. Model training and evaluation
6. Risk interpretation and visualization

---

## Limitations
- Exact earthquake prediction is scientifically impossible.
- Results represent statistical patterns and risk estimation only.

---

## Expected Outcome
- Understanding of Nepal’s earthquake trends
- Severity classification model
- Visual seismic risk insights
- ML pipeline demonstration for seismic data

---

## Future Improvements
- Incorporate real-time seismic feeds
- Improve spatial risk modeling
- Apply time-series forecasting techniques
- Build an interactive dashboard

---

## Author
**Roman Shrestha**  
**Madhav Tharu**  
Electronics, Communication & Information Engineering  
Tribhuvan University, IoE Pashchimanchal Campus
