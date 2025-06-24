# 🚲 Bike Sharing Data Analysis with Python (Cleaning, EDA, Visualization)

## 📌 Overview

This project explores and analyzes the **London Bike Sharing dataset** using Python. The objective is to uncover patterns in bike usage across time, temperature, seasons, and weather conditions, and to demonstrate a typical data analysis pipeline — from loading the data to cleaning, visualization, and extracting insights.

---

## 🛠 Tools & Libraries Used

- **Python 3**
- **Pandas** for data manipulation
- **NumPy** for numerical operations
- **Matplotlib** and **Seaborn** for static data visualization
- **Plotly Express** for interactive visualization
- **KaggleHub** to access the dataset programmatically

---

## 📊 Data Overview

The dataset used is the **London Bike Sharing Dataset**, containing hourly data on bike rentals and various environmental conditions such as:

- `timestamp`: Date and time
- `cnt`: Count of rented bikes
- `t`: Temperature in Celsius
- `hum`: Humidity
- `windspeed`: Wind speed
- `season`, `weekday`, `hour`: Time-based features

---

## 🧹 Data Cleaning with Python

Key steps during data preparation:

- Checked for missing values using `isnull().sum()`
- Converted `timestamp` to datetime format
- Extracted new time-based features: `hour`, `day`, `month`, `year`
- Ensured appropriate data types
- Conducted exploratory value counts and distribution checks

---

## 📈 Data Visualization with Python

Various visualization techniques were used to uncover patterns:

- **Line plots** to show trends in bike usage over time
- **Heatmaps** to highlight bike demand by hour and weekday
- **Boxplots** for seasonal usage distributions
- **Scatter plots** for relationships between temperature and usage
- **Correlation heatmaps** to understand variable relationships

---

## 🔑 Key Insights

- Bike usage is **higher during commuting hours** (around 8 AM and 5–6 PM)
- **Temperature** shows a positive correlation with bike rentals
- **Weekdays** vs **weekends** show distinct patterns
- **High humidity and wind** tend to decrease usage
- **Summer** months see significantly more activity

---
