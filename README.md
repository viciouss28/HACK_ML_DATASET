# Hack-ML — Dataset Overview

Welcome to the **Hack-ML Dataset Repository**.

This repository contains six curated datasets covering different real-world machine learning problems. Each dataset is designed to test participants' ability to perform data preprocessing, exploratory data analysis, feature engineering, model building, and evaluation.

---

## 📂 Repository Structure

Each dataset folder contains:

```text
DatasetName/
├── train.csv
├── test.csv
├── test_labels.csv
└── data_dictionary.csv
```

### Files

| File                  | Description                                            |
| --------------------- | ------------------------------------------------------ |
| `train.csv`           | Training data containing the target variable           |
| `test.csv`            | Test data without the target variable                  |
| `test_labels.csv`     | Actual target values corresponding to the test dataset |
| `data_dictionary.csv` | Description and data type of each column               |

> **Note:** `test_labels.csv` contains the actual target values for `test.csv` and is provided for evaluation/reference purposes.

---

## 📊 Dataset Overview

| # | Dataset              | Problem Type              | Target Variable          | Evaluation Metric |
| - | -------------------- | ------------------------- | ------------------------ | ----------------- |
| 1 | **AirQuality**       | Regression                | `CO(GT)`                 | RMSE              |
| 2 | **FordCars**         | Regression                | `price`                  | RMSE              |
| 3 | **CropYield**        | Regression                | `Yield_tons_per_hectare` | RMSE              |
| 4 | **DiabetesHealth**   | Multiclass Classification | `Diabetes_012`           | Macro F1          |
| 5 | **ShopperIntent**    | Binary Classification     | `Revenue`                | F1 Score          |
| 6 | **NetworkIntrusion** | Binary Classification     | `label`                  | F1 Score          |

---

## 1. 🌫️ AirQuality

### Objective

Predict the **carbon monoxide (CO) concentration** based on air-quality sensor measurements and environmental conditions.

* **Problem Type:** Regression
* **Target:** `CO(GT)`
* **Evaluation Metric:** RMSE

The dataset contains measurements related to pollutants, sensor readings, temperature, humidity, and atmospheric conditions.


---

## 2. 🚗 FordCars

### Objective

Predict the **price of a Ford vehicle** using information such as model, year, mileage, transmission, fuel type, engine size, and other vehicle characteristics.

* **Problem Type:** Regression
* **Target:** `price`
* **Evaluation Metric:** RMSE

The dataset contains a mixture of numerical and categorical features, requiring appropriate preprocessing before model training.

---

## 3. 🌾 CropYield

### Objective

Predict the **crop yield in tons per hectare** based on environmental, agricultural, and cultivation-related factors.

* **Problem Type:** Regression
* **Target:** `Yield_tons_per_hectare`
* **Evaluation Metric:** RMSE

The dataset contains information about regions, soil types, crops, rainfall, temperature, fertilizer usage, irrigation, weather conditions, and harvesting time.

---

## 4. 🩺 DiabetesHealth

### Objective

Predict the **diabetes status** of an individual based on health, lifestyle, demographic, and medical indicators.

* **Problem Type:** Multiclass Classification
* **Target:** `Diabetes_012`
* **Evaluation Metric:** Macro F1 Score

### Target Classes

```text
0 → No Diabetes
1 → Prediabetes
2 → Diabetes
```

The dataset contains health and lifestyle indicators such as BMI, blood pressure, cholesterol, physical activity, general health, age, education, and income category.


---

## 5. 🛒 ShopperIntent

### Objective

Predict whether an online shopping session will result in a **purchase** based on browsing behavior and visitor information.

* **Problem Type:** Binary Classification
* **Target:** `Revenue`
* **Evaluation Metric:** F1 Score

### Target Classes

```text
False → No Purchase
True  → Purchase
```

The dataset contains information about administrative, informational, and product-related pages visited, session duration, bounce rates, exit rates, visitor type, traffic source, operating system, browser, and other session characteristics.


---

## 6. 🛡️ NetworkIntrusion

### Objective

Detect whether a network connection represents **normal traffic or an attack** using network-flow and connection-level characteristics.

* **Problem Type:** Binary Classification
* **Target:** `label`
* **Evaluation Metric:** F1 Score

### Target Classes

```text
0 → Normal Traffic
1 → Attack
```

The dataset contains network characteristics such as protocol, service, connection state, packet counts, byte counts, connection rates, TCP statistics, packet timing, and network-flow statistics.

> **Note:** The `attack_cat` field is excluded from the participant dataset because it directly describes the attack category and could introduce target leakage when predicting `label`.


---

# ⚠️ Important Notes

* The target variable is provided in `train.csv`.
* The target variable is not provided in `test.csv`.
* `test_labels.csv` contains the actual target values corresponding to `test.csv`.
* Do not modify the test-set IDs.
* Participants are responsible for handling missing values and preprocessing.
* Participants may use appropriate machine learning algorithms and feature-engineering techniques.


---

# 🚀 Good Luck!

Explore the data, build your models, experiment with different approaches, and most importantly — have fun solving real-world machine learning problems!

**Happy Modeling! 🤖**
