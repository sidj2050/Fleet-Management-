📌 Overview
A car sharing fleet earns only when its cars are booked. With premium, hybrid and economy cars in one fleet, a single utilisation number hides which cars and zones earn and which sit idle. This project measures performance by car class, zone and hour, and turns each finding into an action.


🎯 Objectives
Track fleet utilisation and idle hours by zone and car class
Compare profit per trip across MINI, hybrid and economy cars
Spot seasonal demand patterns, such as convertibles in summer
Find where and why bookings fail
Identify active, at risk and lapsed customers
Forecast daily trips for the next 30 days


🗂️ Dataset
Synthetic data for 1 April to 30 September 2026, stored in one Excel file with four sheets.

Sheet	Rows	Description
Cars	200	Car ID, class, fuel type, zone
Customers	4,000	Customer ID, city, signup date
Trips	55,416	Car, customer, date, hour, duration, distance, revenue and trip costs
Booking_Attempts	65,189	Car, date, hour and status (success or failure reason)


🛠️ Tools and Skills
Power BI Desktop, DAX, Power Query, data modelling and Excel.


📊 Dashboard Pages
Page	What it shows
Overview	Total trips, revenue, utilisation, profit per trip, booking success
Idle Cars	Low use cars, utilisation by zone, demand by hour
Profitability	Profit per trip and fuel cost per km by car class
Convertibles	MINI Convertible demand by month, weekday and hour
Booking Success	Failed bookings by zone and reason
Retention	Active, at risk and lapsed customers
Forecast	30 day trip forecast with a weekly pattern


💡 Key Insights
Fleet utilisation is about 15%, with Dubai Marina and Downtown well above Sharjah and Deira
MINI cars earn the most per trip but are used the least; Economy is busiest with the thinnest margin
Convertible demand falls about 60% in summer, and evenings hold up better than midday
Booking success is about 85%, with failures concentrated in Business Bay and Sharjah
About 30% of customers have lapsed and 13% are at risk, so the at risk group is the first win back target
