# Hotel Booking Cancellation Analysis and Revenue Optimization

## Project Overview

Hotel reservation cancellations significantly impact revenue and room utilization for both City Hotels and Resort Hotels. This project analyzes historical hotel booking data to identify the key factors influencing cancellations and provides data-driven business recommendations to reduce cancellation rates and improve revenue efficiency.

The analysis focuses on pricing behavior, seasonality, booking channels, customer location, and hotel type using exploratory data analysis (EDA).

## Dataset

Source: Hotel Booking Dataset (2015–2017)    
Records: 119,000+ hotel bookings    

### Key Features:

Hotel type (City / Resort)
Average Daily Rate (ADR)
Booking status (Canceled / Not Canceled)
Booking channels (Online TA, Offline TA, Direct, Groups)
Customer country
Reservation month and lead time

## Tools & Technologies

Programming Language: Python    
Libraries: Pandas, NumPy, Matplotlib, Seaborn    
Environment: Jupyter Notebook   

## Business Questions Addressed

What factors influence hotel booking cancellations?
How do pricing and seasonality affect cancellation behavior?
Which booking channels and regions contribute most to cancellations?
How can hotels optimize pricing and promotional strategies to reduce cancellations?

## Key Insights
- ~37% of hotel bookings are cancelled, causing significant revenue loss
- Higher Average Daily Rate (ADR) strongly correlates with higher cancellation rates
- January has the highest cancellations, while August has the highest confirmed bookings
- Resort hotels show a higher cancellation ratio than city hotels
- Online Travel Agencies contribute the majority of cancellations

## Repository Structure
hotel-booking-cancellation-analysis/   
│   
├── data/    
│ └── hotel_bookings.csv   
├── notebook/    
│ └── hotel_booking_eda.ipynb    
├── report/    
│ └── hotel_cancellation_analysis.pdf    
└── README.md    

## Conclusion
