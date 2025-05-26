# Hotel-booking-cancellation-analysis
## Objective
To analyze hotel booking data to uncover key factors contributing to high cancellation rates and propose actionable business recommendations to minimize cancellations and increase revenue.
## Project Steps
1.	Problem Statement Definition
o	The business challenge is the high cancellation rate of hotel bookings, impacting revenue and room utilization.
2.	Data Collection
o	Dataset: Hotel Booking Demand Dataset from Kaggle
o	~120,000 records, 36 features
3.	Assumptions
o	No external events (e.g., pandemics or policy changes) affected the data.
o	The dataset reflects actual booking behavior.
o	No significant reporting errors from hotels.
4.	Research Questions
o	What are the main reasons for hotel booking cancellations?
o	Does the hotel type (Resort vs. City) affect the cancellation rate?
o	Do prices, booking months, or booking sources impact cancellations?
5.	Hypotheses
o	Higher prices lead to more cancellations.
o	Online travel agents result in more cancellations than direct bookings.
o	City hotels have a higher cancellation rate than resort hotels.
6.	Data Cleaning & Preprocessing
o	Dropped columns: agent, company (high missingness)
o	Handled missing values (children, country)
o	Converted reservation_status_date to datetime
o	Removed extreme outliers from adr (average daily rate)
7.	Exploratory Data Analysis (EDA)
o	Used Pandas, Matplotlib, and Seaborn to:
-	Identify cancellation trends by month
-	Compare cancellation rates between hotel types
-	Analyze the impact of price on cancellations
-	Visualize booking patterns across countries
8.	Key Visualizations
o	Reservation Status Count Bar Chart
o	Cancellations by Hotel Type
o	Monthly Cancellation Trends
o	ADR vs Cancellation Rate Line Graph
o	Pie chart of top countries by cancellation rate
9.	Findings & Insights
o	37% of bookings were canceled — a significant business impact.
o	City hotels have a higher cancellation rate than resort hotels.
o	Cancellations peak in January and dip in August.
o	Price sensitivity is a major driver of cancellations.
o	Portugal had the highest national cancellation rate (~70%).
o	Majority of cancellations came through online channels.
10.	Business Recommendations
o	Adjust pricing strategy during high-cancellation months.
o	Enhance the accuracy of online listings to reduce mismatched expectations.
o	Target price-sensitive customers with promotions in low-booking months.
o	Explore loyalty programs to reduce cancellation behavior.

