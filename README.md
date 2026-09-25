# 🚦 Traffic Flow Prediction

## 📌 Overview

Traffic Flow Prediction is a machine learning project that analyzes vehicle traffic data and predicts different traffic situations using Python and Scikit-learn.

The project performs data preprocessing, exploratory data analysis (EDA), visualization, feature engineering, and machine learning model development using a Random Forest Classifier.

---

## 🎯 Objectives

- Analyze traffic patterns based on time and vehicle counts.
- Identify relationships between different types of vehicles.
- Explore traffic conditions across different days and time periods.
- Build a machine learning model to predict traffic situations.
- Identify the most important features influencing traffic conditions.

---

## 🛠️ Technologies Used

- **Python**
- **Pandas** – Data manipulation and preprocessing
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Scikit-learn** – Machine learning
- **Jupyter Notebook** – Development environment

---

## 📂 Dataset

The project uses a traffic dataset containing information about:

- Time
- Date
- Day of the week
- Car count
- Bike count
- Bus count
- Truck count
- Total vehicle count
- Traffic situation

The dataset is included in this repository as:

`TrafficDataset.csv`

---

## 🔄 Project Workflow

### 1. Data Loading

The traffic dataset is loaded using Pandas.

### 2. Data Preprocessing

The following preprocessing steps were performed:

- Converted the `Time` column into minutes.
- Converted the `Date` column into a numerical representation based on days from a reference date.
- Encoded categorical variables using `LabelEncoder`.
- Checked dataset shape and data types.
- Generated descriptive statistics.

### 3. Exploratory Data Analysis

Several visualizations were created to understand traffic patterns:

- Vehicle Counts Over Time
- Total Vehicles by Day of the Week
- Correlation Heatmap
- Traffic Situation Distribution
- Pairplot
- Time Distribution by Traffic Situation
- Average Traffic Situation by Time

### 4. Feature Engineering

The following features were used for model training:

```text
Time
Day of the week
CarCount
BikeCount
BusCount
TruckCount
Date
