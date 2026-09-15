# 🚗 EV Car India Dataset

## 📌 Overview

The **EV Car India Dataset** contains information about electric vehicles (EVs) available in India. It includes important specifications such as brand, model, price, driving range, power, and battery capacity.

This dataset can be used for **Data Analytics, Data Visualization, Machine Learning, Electric Vehicle Analysis, Price Prediction, and EV Comparison**.

---

## 📊 Dataset Information

| Property | Details |
|---|---|
| Dataset Name | EV Car India Dataset |
| Number of Records | 26 |
| Number of Features | 6 |
| File Format | CSV |
| Domain | Electric Vehicles / Automobile |
| Country | India |

---

## 📋 Features

The dataset contains the following columns:

| Column | Description |
|---|---|
| `Brand` | Name of the EV manufacturer |
| `Model` | Model name of the electric vehicle |
| `Price` | Price of the EV |
| `Range` | Driving range of the vehicle |
| `Power` | Motor power of the vehicle |
| `Battery` | Battery capacity of the vehicle |

---

## 🚘 Sample Data

| Brand | Model | Price | Range | Power | Battery |
|---|---|---:|---:|---:|---:|
| Maruti | SuzukieVitara | 15.99 | 440 | 142 | 49 |
| Tata | PunchEV | 9.69 | 275 | 87 | 30 |
| Mahindra | XEV9e | 21.90 | 542 | 228 | 59 |

---

## 🎯 Possible Uses

This dataset can be used for:

- 📊 Electric vehicle data analysis
- 📈 Price and range comparison
- 🔋 Battery capacity analysis
- ⚡ Power and performance analysis
- 🚘 EV brand comparison
- 🤖 Machine Learning projects
- 💰 EV price prediction
- 📉 Data visualization
- 🔍 Finding the best EV based on specifications

---

## 🧠 Example Analysis Questions

Some possible questions that can be explored using this dataset:

1. Which EV has the highest driving range?
2. Which brand has the most EV models?
3. What is the average EV price?
4. What is the relationship between battery capacity and range?
5. Which EV has the highest motor power?
6. Which EV provides the best range for its price?
7. How does battery capacity affect vehicle range?
8. Which brands offer affordable EVs?
9. What is the average battery capacity of the EVs?
10. Which EV has the best overall specifications?

---

## 🛠️ Technologies That Can Be Used

The dataset can be analyzed using:

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook / Google Colab**
- **Machine Learning**

---

## 💻 Example Python Code

```python
import pandas as pd

# Load dataset
df = pd.read_csv("ev_car_India_dataset.csv")

# Display first 5 rows
print(df.head())

# Display dataset information
print(df.info())

# Display statistical summary
print(df.describe())
