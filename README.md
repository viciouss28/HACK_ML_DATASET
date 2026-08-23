# Hack-ML — Problem Statements & Dataset Overview

Welcome to the **Hack-ML: Machine Learning Hackathon Repository**.

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

## The Problem Domains

Below are **6 predefined problem tracks**, and **Track 7 is Open Innovation**. 

Choose your domain, explore the data, formulate your machine learning strategy, and build a solution that scales. 

| # | Track / Domain | Core Challenge |
| - | :--- | :--- |
| 1 | **AirQuality:** Breathe Easy | Forecast localized pollution levels based on sensor arrays. |
| 2 | **FordCars:** Automotive Valuations | Build a dynamic valuation model for the used car market. |
| 3 | **CropYield:** Next-Gen Agriculture | Predict agricultural output to optimize resource distribution. |
| 4 | **DiabetesHealth:** Preventative Care | Identify at-risk patients using lifestyle and demographic data. |
| 5 | **ShopperIntent:** E-Commerce | Predict user conversion and purchasing behavior. |
| 6 | **NetworkIntrusion:** Cyber Defense | Detect malicious anomalies in network traffic flows. |
| 7 | **Open Innovation:** Bring Your Own Data | Define your own problem statement, source your dataset, and build a unique solution. |

---

### Challenge 1:  AirQuality 
**The Objective:** Build a model to forecast the concentration of Carbon Monoxide (CO) in the atmosphere based on deployed air-quality sensors and environmental conditions.
* **The Data:** Multi-sensor pollutant readings, temperature, relative humidity, and atmospheric conditions.
* **The Impact:** Accurate localized forecasting helps municipalities issue health warnings and optimize traffic flow to reduce smog.

### Challenge 2:  FordCars
**The Objective:** Build a dynamic pricing model that can accurately predict the resale value of Ford vehicles.
* **The Data:** A mix of vehicle characteristics including model, year, mileage, transmission, fuel type, and engine size.
* **The Impact:** Car valuation is highly subjective; algorithmic pricing helps marketplaces ensure fair trade and liquid markets.

### Challenge 3:  CropYield
**The Objective:** Forecast crop yields (tons per hectare) by analyzing complex environmental, agricultural, and cultivation factors.
* **The Data:** Highly dimensional data covering soil types, rainfall, temperature, fertilizer usage, irrigation methods, and harvest timings.
* **The Impact:** Predictive agriculture is the key to global food security and helping farmers make data-driven planting decisions.

### Challenge 4:  DiabetesHealth
**The Objective:** Predict an individual's diabetes status using various lifestyle, demographic, and medical indicators.
* **The Data:** Health markers including BMI, blood pressure, cholesterol, physical activity, income, and education categories.
* **The Impact:** Early identification allows healthcare providers to intervene with preventative care before chronic conditions fully develop. 

### Challenge 5:  ShopperIntent
**The Objective:** Analyze online browsing sessions to predict whether a user's intent will ultimately convert into a successful purchase.
* **The Data:** Session durations, bounce rates, exit rates, page types visited, traffic sources, and browser/OS information.
* **The Impact:** Understanding real-time intent allows e-commerce platforms to trigger timely interventions, like targeted discounts, to save dropping carts.

### Challenge 6:  NetworkIntrusion
**The Objective:** Build an automated defense model capable of distinguishing between normal, safe network traffic and malicious cyber attacks.
* **The Data:** Connection-level characteristics including packet counts, byte counts, connection rates, and TCP statistics. 
* **The Impact:** Threat actors move too fast for manual security. Automated anomaly detection is the critical first line of defense for modern servers.

### Challenge 7:  Open Innovation
**The Objective:** Have a groundbreaking idea that doesn't fit the tracks above? This is your sandbox. Define your own problem statement, source a publicly available dataset, and build a unique machine learning solution.
* **The Data:** Bring your own data (BYOD). Ensure the dataset is publicly accessible and ethically sourced.
* **The Impact:** Limitless. Show the judges a novel application of AI/ML in a domain you are passionate about!
  
---

# Important Notes

* The target variable is provided in `train.csv`.
* The target variable is not provided in `test.csv`.
* `test_labels.csv` contains the actual target values corresponding to `test.csv`.
* Do not modify the test-set IDs.
* Participants are responsible for handling missing values and preprocessing.
* Participants may use appropriate machine learning algorithms and feature-engineering techniques.


---

#  Good Luck!

Explore the data, build your models, experiment with different approaches, and most importantly — have fun solving real-world machine learning problems!

**Happy Modeling!**
