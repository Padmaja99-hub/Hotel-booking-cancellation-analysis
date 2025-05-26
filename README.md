# Hotel-booking-cancellation-analysis
## Objective
To analyze hotel booking data to uncover key factors contributing to high cancellation rates and propose actionable business recommendations to minimize cancellations and increase revenue.

## 📌 Problem Statement Definition

- The business challenge is the high cancellation rate of hotel bookings, impacting revenue and room utilization.

## 📊 Data Collection

- **Dataset**: Hotel Booking Demand Dataset from [Kaggle](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand)
- ~120,000 records, 36 features

## 🧾 Assumptions

- No external events (e.g., pandemics or policy changes) affected the data.
- The dataset reflects actual booking behavior.
- No significant reporting errors from hotels.

## ❓ Research Questions

- What are the main reasons for hotel booking cancellations?
- Does the hotel type (Resort vs. City) affect the cancellation rate?
- Do prices, booking months, or booking sources impact cancellations?

## 🔍 Hypotheses

- Higher prices lead to more cancellations.
- Online travel agents result in more cancellations than direct bookings.
- City hotels have a higher cancellation rate than resort hotels.

## 🧹 Data Cleaning & Preprocessing

- Dropped columns: `agent`, `company` (high missingness)
- Handled missing values (`children`, `country`)
- Converted `reservation_status_date` to datetime
- Removed extreme outliers from `adr` (average daily rate)

## 📈 Exploratory Data Analysis (EDA)

Used **Pandas**, **Matplotlib**, and **Seaborn** to:

- Identify cancellation trends by month
- Compare cancellation rates between hotel types
- Analyze the impact of price on cancellations
- Visualize booking patterns across countries

## 📊 Key Visualizations

- Reservation Status Count Bar Chart
- Cancellations by Hotel Type
- Monthly Cancellation Trends
- ADR vs Cancellation Rate Line Graph
- Pie Chart of Top Countries by Cancellation Rate

## 💡 Findings & Insights

- **37%** of bookings were canceled — a significant business impact.
- **City hotels** have a higher cancellation rate than resort hotels.
- Cancellations peak in **January** and dip in **August**.
- **Price sensitivity** is a major driver of cancellations.
- **Portugal** had the highest national cancellation rate (~70%).
- Majority of cancellations came through **online channels**.

## 📌 Business Recommendations

- Adjust pricing strategy during high-cancellation months.
- Enhance the accuracy of online listings to reduce mismatched expectations.
- Target price-sensitive customers with promotions in low-booking months.
- Explore loyalty programs to reduce cancellation behavior.





