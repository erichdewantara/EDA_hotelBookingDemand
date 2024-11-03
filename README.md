# **HOTEL BOOKING EXPLORATORY DATA ANALYSIS**
This dataset contains booking information for a city hotel and a resort hotel from [Kaggle](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand/data). It is originally from the article written by Nuno Antonio, Ana de Almeida, and Luis Nunes for [Data in Brief, Vol. 22, 2019](https://www.sciencedirect.com/science/article/pii/S2352340918315191).

## Background
The hospitality sector offers diverse accommodation experiences taht cater to various types of travelers. City hotels, often situated within vibrant urban centers, blend modern amenities with local charm, providing travelers with easy access to historic neighborhoods, landmarks, and cultural hotspot. For instance, City Hotel in Lisbon allows guests to enjoy modern comfort amidst iconic in scenic coastal regions like the Algarve, offer serene escapes that emphasize relaxation and outdoor adventure, drawing travelers in search of leisure and scenic beauty.

Hotels generate revenue from guests who stay and spend on additional services provided by the hotel. However, cancellations are inevitable. When cancellations occur too frequently, they can pose a significant challenge for the hotel. Excessive cancellations prevent the hotel from reaching its full income potential.

## Business Problem
From 2015 to 2017, hotels experienced a high number of booking cancellations, both at Resort Hotels and City Hotels. This situation could lead to a reduction in potential revenue from non-room services, such as food and special requests from guests, including room service and cleaning.

## Goals
This analysis aims to help City Hotel and Resort Hotel achieve their maximum potential revenue by identifying factors influencing booking cancellations and recommending data-driven strategies to minimize them.

## Insight
1. **Booking cancellation**: 26.06 percent of bookings were canceled in Resort Hotel, while 30.82 percent of bookings were canceled in City Hotel.
2. **Seasonal Trend**: Most cancellations occured between July and September, with a significant decrease from November to February.
3. **cancellation by Region**: Most cancellations were made by European tourists, especially domestic travelers from Lisbon.
4. **Revenue Impact**: The hotel loss lots of potential revenue, evident from the ADR difference between canceled and non canceled bookings. This could be a huge blow to the hotel's financial stability, potentially impacting it's ability to operate in the future.
5. **Profitability and Frequency**: City Hotel is more profitable, twice as much as Resort Hotel, but experiences cancellations more frequently.
6. **Lead Time Effect**: A longer lead time (the time between the booking made and arrival) leads to a higher booking cancellations.

## Recommendation
1. The hotel should consider limiting the advance hotel booking, ideally allowing bookings no more than 3 months before the arrival.
2. The hotel should also send reminders 1 month, 2 weeks, and the day before arival date, in case guests forget their booking. Reminders can be made via email and/or messaging platform.
3. The hotel could add promotion for Resort Hotel, such as room rates and additional requests, during July and August when ADR is at its peak.
4. To minimize booking cancellations, the hotel should revise its deposit policy. A full refund can be provided for cancellations made at least one month before the arrival date, a 50% for 2 weeks prior, and no refund for cancellations made within 3 days of arrival.

## Dashboard
See the dashboard on [Looker](https://lookerstudio.google.com/s/knSbv8CgBe4)
![image](https://github.com/user-attachments/assets/17696eeb-3459-43cc-8ece-0916402559d9)
