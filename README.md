# Flight Delay Forecasting using Time Series Analysis

## 📘 Overview
This project applies **Time Series Analysis (TSA)** and **Deep Learning (LSTM)** techniques to analyze and forecast flight delays in the United States. 
The objective is to identify patterns, seasonality, and trends in daily flight delay data and build a robust predictive model for future delay estimation.

## 📊 Dataset
The dataset consists of U.S. domestic flight data, containing flight dates (YEAR, MONTH, DAY) and delay information.
Data preprocessing involved combining date columns into a single datetime index and aggregating the total number of delayed flights per day.

## 🧠 Methodology
- Conducted **Exploratory Data Analysis (EDA)** to visualize delay patterns and trends.  
- Performed **ADF (Augmented Dickey-Fuller)** test to check stationarity.  
- Plotted **ACF** and **PACF** graphs to detect autocorrelation and seasonality.  
- Built and trained an **LSTM (Long Short-Term Memory)** model using TensorFlow and Keras for time series forecasting.  
- Scaled data using **MinMaxScaler** and optimized hyperparameters for improved accuracy.

## ⚙️ Technologies Used
- **Python**
- **Pandas**, **NumPy**
- **Statsmodels**, **Matplotlib**, **Seaborn**
- **TensorFlow**, **Keras**
- **Scikit-learn**

## 🚀 Results
The LSTM model effectively captured complex temporal dependencies and outperformed traditional statistical approaches in predicting daily flight delays.  
Visualizations and metrics demonstrate improved forecasting accuracy and valuable insights for aviation operations and management.

## 📂 Project Structure
```
TSA_Assignment.ipynb    # Jupyter Notebook with complete code and analysis
README.md                # Project documentation
```
## 🏷️ Author
Developed by **Meet Prajapati**  
"""

# Save the README file
readme_path = Path("/mnt/data/README.md")
readme_path.write_text(readme_content, encoding="utf-8")

readme_path
#Data set file
https://drive.google.com/file/d/1f0CYWY0tmOTRvCZqPtUJNLoomcUKvU2i/view?usp=sharing
