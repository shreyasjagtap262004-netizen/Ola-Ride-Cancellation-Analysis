# Ola Ride Cancellation Analysis Dashboard

## Problem Statement

Ride cancellations and incomplete rides negatively impact customer satisfaction, driver productivity, and company revenue. The goal of this project is to analyze ride booking data, identify the major reasons behind ride cancellations, and provide actionable insights to improve ride completion rates and operational efficiency.

## Project Objective

- Analyze booking status and ride completion trends.
- Identify key reasons for customer and driver cancellations.
- Examine incomplete ride patterns.
- Evaluate booking value across different vehicle types.
- Study customer payment preferences.
- Build an interactive Power BI dashboard for business insights.

## Dataset Information

**Original Dataset:** `ncr_ride_bookings.csv`

**Cleaned Dataset:** `ncr_ride_bookings_cleaner.xlsx`

- Original Records: 150,000
- Final Records: 150,000
- Original Columns: 21
- Final Columns: 16

## Data Cleaning & Preprocessing

The raw dataset was cleaned and transformed to ensure data quality, consistency, and reliability for analysis and dashboard development.

### Cleaning Steps Performed

- Removed duplicate records.
- Identified and handled missing (NULL) values.
- Standardized date and time formats.
- Corrected inconsistent text values and categories.
- Validated booking value, ratings, and ride distance fields.
- Merged and organized related columns where required.
- Checked data integrity across booking status, payment methods, and vehicle types.
- Prepared the dataset for Power BI reporting.

### Columns Removed

- Booking ID
- Customer ID
- Cancelled Rides by Customer
- Cancelled Rides by Driver
- Incomplete Rides

### Final Columns Available

- Date
- Time
- Booking Status
- Vehicle Type
- Pickup Location
- Drop Location
- Avg VTAT
- Avg CTAT
- Reason for Cancelling by Customer
- Driver Cancellation Reason
- Incomplete Ride Reason
- Booking Value
- Ride Distance
- Driver Ratings
- Customer Rating
- Payment Method

## Dashboard KPIs

- Average Customer Turnaround Time (CTAT)
- Average Customer Rating
- Total Orders
- Booking Status Distribution
- Booking Value by Vehicle Type
- Payment Method Analysis
- Monthly Incomplete Ride Trends
- Average Vehicle Turnaround Time (VTAT)

## Key Insights

- Completed rides account for the majority of bookings.
- Customer and driver cancellations contribute significantly to ride losses.
- Auto and Go Mini generate the highest booking values.
- UPI is the most preferred payment method.
- Ride cancellation trends vary by month and vehicle category.

## Tools & Technologies

- Microsoft Excel
- SQL
- Power BI

## Repository Structure

Ola-Ride-Cancellation-Analysis/

├── data/

│   ├── ncr_ride_bookings.csv

│   └── ncr_ride_bookings_cleaner.xlsx

├── dashboard/

│   └── Ola_Ride_Analysis.pbix

├── screenshots/

│   └── dashboard.png

└── README.md

## Conclusion

This project helps identify ride cancellation patterns and provides insights that can improve ride completion rates, customer satisfaction, and operational efficiency.
