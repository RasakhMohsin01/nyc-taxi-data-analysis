# 🚕 NYC Taxi Dataset - Exploratory Data Analysis & Visualization

An end-to-end data analysis project exploring New York City taxi trip patterns, fare structures, peak demand hours, and passenger tipping behaviors using Python.

---

## 📊 Overview & Objectives
This project analyzes a dataset of **6,400+ NYC taxi trips** to answer key operational and financial questions:
* **Demand Patterns:** When are taxis most in demand across days of the week and hours of the day?
* **Fare Drivers:** How strongly do trip distance and duration correlate with total cost?
* **Tipping Behavior:** How do passenger tips vary by payment method (credit card vs. cash) and pickup location?
* **Taxi Types:** What are the key operational differences between Yellow and Green taxis?

---

## 🛠️ Tools & Libraries Used
* **Python 3.x**
* **Pandas & NumPy:** Data cleaning, manipulation, and feature engineering.
* **Seaborn & Matplotlib:** Univariate, bivariate, and multivariate data visualizations.
* **Jupyter Notebook:** Interactive development and workflow.

---

## 🧹 Key Data Preprocessing Steps
1. **Missing Values & Duplicates:** Handled null values in payment and location zones; removed duplicate records.
2. **Feature Engineering:** Extracted `pickup_hour`, `day_of_week`, and calculated `trip_duration_min`.
3. **Outlier Filtering:** Filtered out logical errors ($0 fare/distance) and capped extreme trip durations and price outliers using the **Interquartile Range (IQR)** method.

---

## 📈 Key Insights & Findings
* **Peak Demand:** Ride volume peaks between **4:00 PM – 7:00 PM** on Thursdays and Fridays.
* **Pricing Dynamics:** Strong positive correlation ($\sim 0.8–0.9$) between trip distance, base fare, and total cost.
* **Airport & Outer Borough Trips:** Rides originating from Queens (JFK/LaGuardia) yield the highest average total fares and tips.
* **Yellow vs. Green Taxis:** Yellow taxis handle longer-distance and higher-fare trips, while Green taxis focus mainly on shorter, local trips.

---

## 👤 Author
* **Name:** Rasakh Mohsin (*Ryzek_20*)
* **Kaggle:** [RasakhMohin](https://www.kaggle.com/rasakhmohsin01)
