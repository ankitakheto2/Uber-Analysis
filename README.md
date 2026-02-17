# 🚖 Uber Ride Analysis Dashboard – Power BI

## 📌 Overview
This is an interactive Uber Ride Analysis Dashboard built using Power BI.
The dashboard analyzes bookings, revenue, vehicle performance, and customer behavior to generate meaningful business insights.

## 🛠 Tools & Technologies
- Power BI Desktop
- DAX (Data Analysis Expressions)
- Power Query
- Star Schema Data Modeling

## 📊 Key Metrics
- Total Bookings
- Completed Bookings
- Lost Bookings
- Total Revenue
- Total Distance
- Average Distance
- Customer Rating
- Driver Rating

## 📈 Key Insights
- Auto generates the highest revenue.
- UPI is the most preferred payment method.
- Most bookings are completed successfully.
- Q2 shows the highest booking performance.
- Uber XL contributes the lowest revenue.

## 🧠 Sample DAX Measures

Total Revenue = SUM(Bookings[Revenue])

Completed Bookings =
CALCULATE(
    COUNT(Bookings[Booking ID]),
    Bookings[Status] = "Completed"
)

Lost Bookings =
CALCULATE(
    COUNT(Bookings[Booking ID]),
    Bookings[Status] = "Cancelled"
)

## 🎯 Objective
To monitor ride performance, analyze revenue trends, and understand customer preferences for better decision-making.

## 👩‍💻 Author
Ankita Kheto
Aspiring Data Analyst
