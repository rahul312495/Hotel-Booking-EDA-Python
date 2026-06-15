# Hotel-Booking-EDA-Python
# 🏨 Hotel Booking Analysis | EDA Project

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on hotel booking data to understand customer behaviour, cancellation patterns, seasonal demand, and revenue-impacting factors.

The goal is to identify key business insights that can help hotels improve occupancy planning, revenue management, and cancellation strategies.

---

## 🎯 Business Problem

Hotels face major revenue losses due to booking cancellations because a cancelled room may not be resold at the last moment.

This analysis focuses on answering:

- Why are customers cancelling bookings?
- Which customers are more likely to cancel?
- Which channels create high-risk bookings?
- When is hotel demand highest?
- How can hotels improve revenue forecasting?

---

## 📂 Dataset

**Dataset:** Hotel Booking Demand Dataset (Kaggle)

Details:

- Records: 119,390 bookings
- Features: 32 columns
- Time Period: 2015 - 2017
- Hotels:
  - City Hotel
  - Resort Hotel

Dataset contains:

- Customer details
- Booking information
- Room type
- Market segment
- ADR (Average Daily Rate)
- Cancellation status
- Lead time
- Special requests

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Python | Data analysis |
| Pandas | Data cleaning & manipulation |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Jupyter Notebook | Development environment |

---

## 🔎 Data Cleaning & Preprocessing

Performed:

✔ Removed duplicate records  
✔ Handled missing values  
✔ Converted incorrect data types  
✔ Created new features:

- Total Guests
- Total Stay Nights
- Estimated Revenue

After cleaning:

**87,370 unique bookings** were used for analysis.

---

# 📊 Key Insights

## 1. Cancellation Rate

- Overall cancellation rate: **27.5%**

Around 1 out of every 4 bookings was cancelled, creating significant revenue loss.

---

## 2. Hotel Type Comparison

Cancellation rate:

| Hotel Type | Cancellation |
|---|---|
| City Hotel | 30% |
| Resort Hotel | 23.5% |

City hotels experience higher cancellations due to more flexible and short-term bookings.

---

## 3. Seasonal Booking Pattern

- Highest bookings: **August**
- Lowest bookings: **January**

Demand varies significantly across months, impacting staffing and pricing decisions.

---

## 4. Pricing Analysis

Peak season months show higher ADR (Average Daily Rate).

This indicates demand-based pricing opportunities.

---

## 5. Customer Geography

Top booking source country:

🇵🇹 Portugal

Other major markets:

- UK
- France
- Spain
- Germany

---

## 6. Lead Time Impact

Cancelled bookings have higher average lead time.

Customers booking far in advance are more likely to cancel.

---

## 7. Market Segment Analysis

Online Travel Agencies (OTAs):

- Highest booking volume
- Higher cancellation rate

Direct and corporate bookings show better reliability.

---

## 8. Important Features for Future ML Model

Features showing strong relationship with cancellation:

- Lead Time
- Previous Cancellations
- Special Requests

These can be used for building a cancellation prediction model.

---

# 💡 Business Recommendations

### Revenue Protection

Introduce cancellation policies and deposits for high-risk bookings.

### Channel Optimization

Increase direct bookings using loyalty programs and incentives.

### Dynamic Pricing

Adjust room prices according to seasonal demand.

### Risk Prediction

Use customer behaviour data to predict cancellation probability.

---

# 📁 Project Structure
Hotel-Booking-EDA-Python/

│── Hotel_Booking_Analysis.ipynb
│── hotel_bookings.csv
│── README.md
│── Viauals/


---

## 👨‍💻 Author

**Rahul Pawar**

Computer Engineering Student  
Interested in Data Analytics, Business Intelligence & Problem Solving
