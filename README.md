# Hotel-Booking-Data-Analysis
# Hotel Booking Cancellation Analysis

## Overview
This project analyzes hotel booking data to identify factors influencing reservation cancellations. The analysis provides insights into cancellation trends, market segments, pricing impact, and potential strategies to reduce cancellations and improve hotel revenue.

## Dataset
The dataset contains hotel booking records with the following key attributes:
- **Booking Details:** Arrival date, number of nights, booking status.
- **Customer Information:** Lead time, demographics, and room preferences.
- **Market Segment:** Online Travel Agencies (OTA), Groups, Direct bookings, etc.
- **Financial Data:** Average Daily Rate (ADR), deposit type, and cancellation status.

## Business Problem
City Hotel and Resort Hotel have experienced **high cancellation rates**, leading to revenue loss and inefficient room utilization. This analysis aims to provide **data-driven recommendations** to reduce cancellations and optimize pricing strategies.

## Research Questions
1. What are the variables that affect hotel reservation cancellations?
2. How can we minimize hotel reservation cancellations?
3. How can hotels optimize pricing and promotions to reduce cancellations?

## Hypotheses
- Higher prices lead to more cancellations.
- Customers with longer lead times are more likely to cancel.
- The majority of bookings come from **offline travel agents**, contributing to cancellations.

## Analysis & Key Insights
- **Overall Cancellation Rate:** 62.87% of total bookings were canceled.
- **City Hotels vs. Resort Hotels:** City Hotels had higher cancellation rates (41.71%) than Resort Hotels (27.98%).
- **Impact of Lead Time:** Cancellations increased with longer lead times.
- **Deposit Type Impact:** No-deposit bookings had the highest cancellation rates.
- **Market Segment Trends:** Groups and OTA bookings had the highest cancellation rates.
- **Price Sensitivity:** Higher ADR bookings had a slightly higher cancellation tendency.

## Visualizations
- Booking Status Distribution (Canceled vs. Not Canceled)
- Cancellation Rate by Hotel Type
- Impact of Lead Time on Cancellations
- Market Segment vs. Cancellation Rate
- ADR Distribution and Cancellation Trends

## Recommendations
- **Early Booking Discounts:** Encourage customers to confirm reservations sooner.
- **Non-Refundable Deposits:** Reduce cancellations by incentivizing deposit-based bookings.
- **Segment-Based Pricing:** Adjust pricing and promotions based on high-cancellation segments.
- **Retention Strategies:** Focus on reducing cancellations for OTA and Group bookings.

## Tools & Technologies
- **Python (Pandas, NumPy, Matplotlib, Seaborn)** for data analysis and visualization.
- **Jupyter Notebook** for interactive analysis.

## How to Run the Project
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/hotel-booking-analysis.git
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```sh
   jupyter notebook
   ```

## Conclusion
This analysis highlights the key drivers of hotel booking cancellations and provides actionable insights for revenue optimization. Future work could explore seasonal trends and customer loyalty programs to further improve retention strategies.

