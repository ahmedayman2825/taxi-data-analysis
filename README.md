# 🚕 NYC Taxi Trip Analysis

<p align="center">
  <img src="screenshots/trips-by-hour.png" width="850">
</p>

<p align="center">
  <b>Exploratory Data Analysis of NYC Taxi Trips using Python</b>
</p>

<p align="center">
  🐍 Python • 📊 Data Analysis • 📈 Visualization • 🧹 Data Cleaning
</p>

---

# 📌 Project Overview

This project analyzes real-world NYC Yellow Taxi trip data to uncover travel patterns, fare behavior, customer payment preferences, and peak demand periods.

The dataset was obtained from Kaggle and contains thousands of taxi trips recorded in New York City.

The project follows a complete Data Analysis workflow:

1. Data Loading
2. Data Exploration
3. Data Cleaning
4. Outlier Detection
5. Visualization
6. Insight Generation

---

# 🎯 Objectives

* Understand NYC taxi usage patterns
* Identify peak travel hours
* Analyze fare distributions
* Study trip distances
* Explore payment methods
* Detect data anomalies and outliers

---

# 📂 Dataset

The dataset contains information about:

* Pickup and Dropoff Time
* Passenger Count
* Trip Distance
* Fare Amount
* Payment Type
* Pickup Location
* Dropoff Location
* Tip Amount
* Total Amount

Dataset Source:

https://www.kaggle.com/datasets/dhruvdre5/new-york-city-taxi-and-limousine-commission-data

---

# 🧹 Data Cleaning

The following preprocessing steps were performed:

✅ Duplicate Removal

✅ Missing Value Analysis

✅ Datetime Conversion

✅ Invalid Trip Removal

✅ Outlier Detection using IQR

✅ Fare Amount Filtering

---

# 📸 Visualizations

## 🚕 Trip Distance Distribution

Distribution of taxi trip distances.

![Trip Distance Distribution](screenshots/trip-distance-distribution.png)

---

## 💰 Fare Amount Distribution

Boxplot showing fare distribution and outliers.

![Fare Boxplot](screenshots/fare-boxplot.png)

---

## ⏰ Trips by Hour

Number of taxi trips recorded during each hour of the day.

![Trips by Hour](screenshots/trips-by-hour.png)

---

## 📏 Trip Distance vs Fare Amount

Relationship between trip distance and fare amount.

![Fare vs Distance](screenshots/fare-vs-distance.png)

---

## 💳 Payment Method Distribution

Distribution of customer payment methods.

![Payment Distribution](screenshots/payment-distribution.png)

---

# 📈 Key Insights

The analysis revealed:

* Peak taxi demand occurs around 7 PM.
* Longer trips generally result in higher fares.
* Most customers use Payment Method 1.
* Most taxi trips are relatively short distances.
* Fare distributions contain several outliers that required cleaning.

---

# 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

# 📚 Skills Demonstrated

* Exploratory Data Analysis (EDA)
* Data Cleaning
* Data Visualization
* Statistical Analysis
* Feature Exploration
* Outlier Detection
* Business Insight Generation

---

# 📁 Repository Structure

```text
nyc-taxi-trip-analysis/
│
├── taxi_analysis.ipynb
├── 2017_Yellow_Taxi_Trip_Data.csv
├── README.md
│
└── screenshots/
    ├── dataset-preview.png
    ├── trip-distance-distribution.png
    ├── fare-boxplot.png
    ├── trips-by-hour.png
    ├── fare-vs-distance.png
    ├── payment-distribution.png
    └── summary-insights.png
```

---

# 🚀 Run Locally

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

Launch Jupyter:

```bash
jupyter notebook
```

Open:

```text
taxi_analysis.ipynb
```

---

# ⭐ Conclusion

This project demonstrates the complete process of transforming raw transportation data into meaningful insights through data cleaning, visualization, and exploratory analysis.
