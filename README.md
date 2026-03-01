# 🌤️ Weather Temperature Prediction



A machine learning project that predicts **air temperature** using a Gradient Boosting Regressor trained on real-world weather data.



---



## 📊 Dataset



- **Source:** [Weather Type Classification – Kaggle](https://www.kaggle.com/datasets/nikhil7280/weather-type-classification)

- **Size:** 13,200 records × 11 features

- **Features:** Humidity, Wind Speed, Precipitation, Cloud Cover, Atmospheric Pressure, UV Index, Season, Visibility, Location, Weather Type

- **Target:** Temperature (°C)



---



## 🔧 What I Did



- Explored and visualized the data (boxplot, describe, info)

- Detected and removed outliers using the **IQR Method**

- Applied **One-Hot Encoding** on categorical features (Season, Location, Weather Type, Cloud Cover)

- Split data 80/20 for Train/Test

- Trained a **Gradient Boosting Regressor**

- Evaluated using Cross Validation (cv=5)

- Visualized **Feature Importance**



---



## 📈 Results



| Metric | Score |
|--------|-------|
| R² Score | **0.694** |
| RMSE | ~7.94 |
| MAE | ~6.389 |
| CV Mean R² | **0.686** (stable across 5 folds) |


---



## 🛠️ Tech Stack



![Python](https://img.shields.io/badge/Python-3.x-blue)

![Pandas](https://img.shields.io/badge/Pandas-darkblue)

![NumPy](https://img.shields.io/badge/Numpy-yellow)

![Scikit--learn](https://img.shields.io/badge/Scikit--learn-orange)

![Matplotlib](https://img.shields.io/badge/Matplotlib-green)



---



## ▶️ How to Run



```bash

# 1. Install dependencies

pip install -r requirements.txt



# 2. Make sure the dataset is in the same folder as the notebook

# Weather_Data.csv



# 3. Open the notebook

jupyter notebook Weather_Regression_Pred.ipynb

```



---



## 📁 Project Structure



```

Weather-Temperature-Prediction/

├── Weather_Regression_Pred.ipynb   # Main notebook

├── Weather_Data.csv # Dataset

├── requirements.txt                # Dependencies

└── README.md                       # You are here

```


