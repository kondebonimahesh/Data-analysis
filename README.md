Ride-Sharing Conversion & Cancellation Analysis (Namma Yatri )


This project analyzes a real-world ride-hailing dataset from the Namma Yatri Datathon 2025 to understand user behavior, identify funnel drop-offs, and investigate booking cancellations.
The goal is to derive data-driven insights and propose strategic interventions to improve conversion rates and reduce cancellations.

Objectives

Analyze the conversion funnel across all ride-stages (Search → Quote → Booking → Completed).

Examine cancellation patterns segmented by driver/rider source, pickup distance, and trip distance.

Identify critical drop-off stages and root causes affecting user engagement.

Perform behavioral segmentation of drivers and riders using clustering techniques.

Visualize insights through interactive dashboards and funnel charts.

Dataset

The dataset includes real trip data from the Namma Yatri platform:

File	Description
search_request.csv	Rider search request details (distance, duration, timestamps).
quote.csv	Quotes offered by drivers (fare, distance_to_pickup, driver_rating).
booking.csv	Booking information with trip status and timestamps.
booking_cancellation_reason.csv	Cancellation source and reasons for canceled rides.


Key Analysis Performed
🔹 Conversion Funnel Deep Dive

Computed conversion rates across all funnel stages.

Segmented data by time-of-day (Morning, Day, Evening, Night) and trip length (Short < 5 km, Medium 5–15 km, Long > 15 km).

Identified the maximum drop-off between Search → Quote and Booking → Completed stages.

🔹 Booking Cancellations

Calculated overall and segmented cancellation rates.

Analyzed top driver cancellation reasons — Traffic Jam, Pickup Too Far, Vehicle Issue.

Explored correlation between driver ratings and cancellation frequency.

🔹 Behavioral Segmentation

Applied KMeans clustering to classify drivers and riders based on activity and cancellation behavior.

🔹 Time-Series Analysis

Resampled weekly data to detect seasonal patterns in conversion and cancellation trends.


Key Insights

Largest drop occurs from Search → Quote stage during evening hours and short trips.

Drivers with lower ratings show higher cancellation rates.

Behavioral clusters revealed distinct segments of high-quote, low-booking drivers.


Learnings

Hands-on experience with real-world messy datasets — cleaning, wrangling, and joining multiple files.

Strengthened EDA, time-series, and clustering skills.

Gained exposure to data storytelling and visualization best practices.
