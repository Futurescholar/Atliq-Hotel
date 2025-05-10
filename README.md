# Project Outline

---
## Project Title:
### Atliq Hotel Performance Analysis – (May – July)

---
## Objective:
To evaluate atliq hotel’s  performance within the months of May to July and identify opportunities to improve customer satisfaction, boost revenue, and reduce revenue leakage through cancellations.
---
## Problem Statement
- How can we improve customer satisfaction and increase average ratings?
- What strategies can improve sales and occupancy?
- How can we reduce revenue loss from cancellations?
- Which locations, room classes, and categories are the most/least profitable?

---
## Tools Used
Power BI (for Data Cleaning, DAX Calculations, and Visualization)

---
## Visualization Approach
- Imported and cleaned data in Power BI’s Power Query.
- Created a central DAX Measures Table for calculated metrics.
  - Added KPI cards for:
  - Revenue Generated – ₹2.01B
  - Lost Revenue – ₹0.30B
  - Average Rating – 3.6
  - Occupancy Rate – 70.15%
  - Cancellation Rate – 24.83%
  - Average Room Capacity – 25
- Built bar charts showing:
  - Ratings by City
  - Revenue Realized by City & Category
  - Total Bookings by Platform
- Added a detailed matrix table showing: Property-level performance including revenue, occupancy, capacity, and cancellations.
- Added filters for: Room Class, Property, Category, City, Week, Day Type, and Booking Status

---
![Overview](Screenshot%20(70).png)
---
## Key Observations
- Delhi has the highest average guest rating (3.8), followed by Hyderabad and Mumbai.
- Luxury category outperforms the business class in revenue generation.
- Mumbai is the top-performing city with ₹0.41B revenue in the Luxury segment alone.
- The “Others” booking platform contributed the highest number of bookings, followed by Makeyourtrip and Logtrip.
- May 2024 was the most profitable month, generating ₹0.68B in revenue.
- Atliq Exotica (Mumbai) was the best-performing hotel with ₹138.6M in generated revenue and ~71% occupancy.
- The cancellation rate (24.83%) is significantly impacting revenue — ₹0.30B lost.
- Room capacity averages around 25, with some properties peaking at 30+.

---
## Summary of Findings
- Overall occupancy rate is strong (70.15%), indicating solid utilization.
- However, a 24.83% cancellation rate is a red flag leading to ₹300M in lost revenue.
- Luxury hotels in Mumbai are driving the most revenue — which shows that’s the hotel’s strength.
- Customer satisfaction, while fair at 3.6/5, can be improved further.
- Booking distribution favors indirect/aggregated platforms, suggesting dependency on third-party sites.

---
## Recommendations
### Reduce Cancellation Loss:
- Introduce non-refundable booking discounts or flexible rescheduling.
- Send timely reminders and offer small incentives to encourage check-in.

### Improve Customer Satisfaction:
- Focus on Bangalore and Mumbai for service quality improvements to match Delhi’s rating.
- Add feedback forms tied to rewards for post-checkout surveys.

### Maximize Revenue in Luxury Segment:
- Upsell and cross-sell in Luxury properties, especially in Mumbai and Hyderabad.
- Expand amenities or loyalty programs for repeat guests in top-performing cities.

### Optimize Booking Channels:
- Negotiate better terms with high-volume platforms like Makeyourtrip.
- Strengthen the hotel’s direct booking system to reduce third-party commissions.

### Capacity Planning:
- Monitor occupancy and room capacity data to avoid overbooking and improve room assignment algorithms.

### Internal Benchmarking:
Use Atliq Exotica Mumbai as a model for underperforming properties in similar markets.

---
## Data Source
Codebasic (Atliq Hotel Booking Dataset)

---
## Technical Details
- Built in Power BI
- Visuals Used: Card KPIs, Bar Charts, Matrix Table
- Techniques Displayed: Power Query Data Cleaning, DAX Measures, Filtering, Drill-through
- Date Range of the Dataset :May to July, 2022

---
