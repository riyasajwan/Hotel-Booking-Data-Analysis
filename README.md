# 🏨 Hotel Booking Data Analysis

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on a hotel booking dataset to uncover booking patterns, customer behavior, cancellation trends, and seasonal demand. The analysis aims to provide actionable business insights that can help hotel management improve customer retention, optimize occupancy, and make data-driven decisions.

---

## 🎯 Objectives

- Analyze hotel booking trends and customer behavior.
- Identify factors contributing to booking cancellations.
- Compare booking patterns between City Hotels and Resort Hotels.
- Study seasonal demand and monthly booking trends.
- Generate business insights and recommendations using data visualization.

---

## 📂 Project Structure

```
Hotel-Booking-Data-Analysis/
│
├── dataset/
│   └── hotel_bookings.csv
│
├── notebook(code)/
│   └── Hotel_Booking_Analysis.ipynb
│
├── images/
│
├── README.md
```

---

## 📊 Dataset

The dataset contains hotel booking records for both **City Hotels** and **Resort Hotels**.

It includes information such as:

- Hotel Type
- Booking Status
- Lead Time
- Arrival Date
- Customer Type
- Market Segment
- Distribution Channel
- Average Daily Rate (ADR)
- Room Type
- Booking Cancellation
- Length of Stay

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🔍 Analysis Performed

### Data Cleaning
- Removed duplicate records
- Handled missing values
- Removed invalid bookings
- Feature engineering

### Exploratory Data Analysis
- Univariate Analysis
- Bivariate Analysis
- Multivariate Analysis

### Business Analysis
- Customer segmentation
- Booking trends
- Cancellation analysis
- Seasonal demand analysis
- Room type analysis
- Lead time analysis
- Average Daily Rate (ADR) analysis
- Correlation analysis

---

## 📈 Key Insights

- City Hotels received significantly more bookings than Resort Hotels.
- Booking demand peaked during the summer months.
- Travel Agents and Tour Operators contributed the highest number of bookings.
- City Hotels experienced a higher cancellation rate.
- Most guests were Transient customers.
- Very few guests were repeat customers, indicating an opportunity to improve customer retention.

---
---

# 📊 Visualizations

### 1. Most Reserved Hotel

This visualization compares the total bookings between **City Hotels** and **Resort Hotels**.

![Most Reserved Hotel](Images/Most%20Reserved%20Hotel.png)

---

### 2. Distribution of Customer Type

Shows the percentage distribution of different customer types such as Transient, Contract, Group, and Transient-Party.

![Distribution of Customer Type](Images/Distribution%20of%20Customer%20Type.png)

---

### 3. Top Ten Booking Agents

Displays the top 10 travel agents based on the number of hotel bookings.

![Top Ten Agents](Images/Top%20Ten%20Agents.png)

---

### 4. Year-wise Bookings

Illustrates the booking trend across different years.

![Year Wise Bookings](Images/Year%20Wise%20Bookings.png)

---

### 5. Total Stay Length Analysis

Shows how the number of bookings varies with the total duration of stay.

![Total Stay Length](Images/Total%20Stay%20Length.png)

---

### 6. Average Daily Rate (ADR) Across Each Month

Shows how the Average Daily Rate changes throughout the year for different hotel types.

![ADR Across Each Month](Images/ADR%20across%20Each%20Month.png)

---

### 7. ADR Across Market Segment

Compares the Average Daily Rate across different market segments.

![ADR Across Market Segment](Images/ADR%20across%20Market%20Segment.png)

---

### 8. Correlation Heatmap

Displays the correlation between numerical variables in the dataset to identify important relationships.

![Correlation Heatmap](Images/Correlation%20Heatmap.png)


