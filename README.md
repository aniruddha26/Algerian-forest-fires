# 🔥 Algerian Forest Fires - Regression Analysis

A machine learning project using **Linear Regression**, **Lasso**, **Ridge**, and **ElasticNet** to analyze and predict fire-related indices from weather data collected in Algeria. This project is part of my learning and practice in machine learning and regression techniques using Python.

> 🧪 This is a practice project aimed at applying and comparing different regression models.

---

## 📌 Objective

To model and analyze the relationship between various weather and fire-related features and the **Fire Weather Index (FWI)** — a key indicator of fire intensity.

---

## 🌍 Dataset Description

The dataset contains **244 instances** from two regions in Algeria:

- **Bejaia** (Northeast Algeria)
- **Sidi Bel-abbes** (Northwest Algeria)

🗓️ **Time Period**: June 2012 to September 2012  
🔢 **Total Samples**: 244 (122 from each region)  
🏷️ **Target Variable**: Fire occurrence class (Fire / Not Fire)  
📈 **Regression Target**: Fire Weather Index (FWI)

### 🔢 Features (11 input + 1 output)

| Feature | Description |
|--------|-------------|
| `Date` | Date of observation (DD/MM/YYYY) |
| `Temp` | Temperature at noon (°C) |
| `RH`   | Relative Humidity (%) |
| `Ws`   | Wind Speed (km/h) |
| `Rain` | Total daily rainfall (mm) |
| `FFMC` | Fine Fuel Moisture Code |
| `DMC`  | Duff Moisture Code |
| `DC`   | Drought Code |
| `ISI`  | Initial Spread Index |
| `BUI`  | Buildup Index |
| `FWI`  | Fire Weather Index (**regression target**) |
| `Classes` | Fire / Not Fire classification |

📂 **Source**: UCI Machine Learning Repository  
[Link to dataset](https://archive.ics.uci.edu/ml/datasets/Algerian+Forest+Fires+Dataset+)

---

## 🧠 Techniques Used

- **Data Preprocessing**:
  - Handling missing values
  - Encoding categorical variables
  - Feature scaling
- **Regression Models**:
  - Linear Regression
  - Ridge Regression
  - Lasso Regression
  - ElasticNet Regression
- **Model Evaluation**:
  - R² Score
  - Mean Squared Error (MSE)
  - Cross-validation

---

## 🚀 Getting Started

### 1. Clone the repository

git clone https://github.com/aniruddha26/Algerian-forest-fires.git
cd Algerian-forest-fires

### 2. Install dependencies

pip install -r requirements.txt

### 3. Run the script or open the notebook

Use Jupyter to explore the project step-by-step

## 📊 Results
Regression models were compared based on error metrics and R² score.

Regularization methods like Ridge, Lasso, and ElasticNet showed improved generalization in some scenarios compared to plain linear regression.

## 📌 Acknowledgements
Dataset: UCI Machine Learning Repository
Algerian Forest Fires Dataset

## 👨‍💻 Author
### Aniruddha Alkari

Feel free to fork this repo, raise issues, or contribute to improve this analysis!


