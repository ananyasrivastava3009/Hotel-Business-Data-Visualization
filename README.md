# 🏨 Hotel Business Data Visualization

## 📌 Project Overview

This project analyzes hotel booking data to identify important business patterns related to hotel popularity, booking seasonality, stay duration, and booking cancellations.

The main objective is to use **Data Analysis and Data Visualization** techniques to answer three important business questions and convert the findings into practical recommendations for hotel management.

---

## 🎯 Business Questions

This project focuses on three major questions:

1. Which hotel type is more popular, and how does booking demand change across months?
2. How does total stay duration affect the cancellation rate?
3. How does lead time affect the cancellation rate?

---

## 📊 Dataset

The project uses the **Hotel Booking Dataset** containing booking information for City Hotel and Resort Hotel.

Important features used in the analysis include:

- `hotel`
- `is_canceled`
- `lead_time`
- `arrival_date_year`
- `arrival_date_month`
- `arrival_date_week_number`
- `arrival_date_day_of_month`
- `stays_in_weekend_nights`
- `stays_in_weekdays_nights`
- `adults`
- `children`
- `babies`
- `meal`
- `market_segment`
- `distribution_channel`
- `customer_type`
- `adr`
- `reservation_status`

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- VS Code
- GitHub

---

## 🔄 Project Workflow

### Stage 1 — Data Preprocessing

The dataset was first inspected and assessed for data quality.

The preprocessing stage included:

- Understanding the dataset structure
- Checking missing values
- Checking duplicate records
- Identifying inconsistent values
- Handling anomalies
- Creating useful derived features such as total stay duration

---

### Stage 2 — Data Analysis

#### 2.1 Monthly Booking Analysis

The analysis compares booking demand between:

- City Hotel
- Resort Hotel

Monthly booking trends were visualized to identify:

- More popular hotel type
- Busiest months
- Quietest months
- Seasonal booking patterns

---

#### 2.2 Stay Duration and Cancellation Analysis

The project analyzes the relationship between total stay duration and cancellation rate.

The analysis includes:

- Cancellation rate by hotel type
- Cancellation rate across different stay durations
- Comparison between City Hotel and Resort Hotel
- Identification of important cancellation patterns

---

#### 2.3 Lead Time and Cancellation Analysis

Lead time represents the number of days between the booking date and the arrival date.

The project analyzes:

- Cancellation rate across different lead times
- Comparison between hotel types
- Lowest cancellation point
- Highest cancellation point
- Changes in cancellation behaviour for advance bookings

---

## 💡 Key Business Insights

The analysis provides insights into:

- Hotel type popularity
- Monthly and seasonal booking demand
- Cancellation behaviour
- Stay-duration patterns
- Lead-time related cancellation risk

These findings can help hotel management make better decisions related to pricing, promotions, booking policies, and cancellation management.

---

## 📈 Business Recommendations

Based on the analysis, the project recommends:

### 1. Improve demand during weaker periods

Hotels can introduce targeted promotions and marketing campaigns during relatively quiet months to improve occupancy.

### 2. Capitalize on peak seasons

Hotels can prepare additional operational capacity and optimize pricing during high-demand periods.

### 3. Reduce cancellation-related revenue loss

Hotels can consider suitable cancellation policies, pricing strategies, and minimum-stay rules where appropriate.

### 4. Manage advance bookings carefully

For bookings made far in advance, hotels can use:

- Booking confirmation messages
- Reminder notifications
- Suitable deposit policies
- Controlled rescheduling options
- Appropriate pricing incentives

These measures can help reduce cancellation risk and protect future revenue.

---

## ⭐ Most Important Recommendation

The most impactful recommendation is to **reduce cancellation risk for bookings made far in advance**.

Lead time is an important factor associated with cancellation behaviour. Therefore, hotels can introduce confirmation reminders, suitable deposit policies, and flexible rescheduling options for advance bookings.

Reducing cancellations can help protect room availability and hotel revenue.

---

## 📁 Project Structure

```text
Hotel-Business-Data-Visualization/
│
├── data/
│   └── hotel_bookings_data.csv
│
├── notebook/
│   └── Hotel_Business_Analysis.ipynb
│
└── README.md
