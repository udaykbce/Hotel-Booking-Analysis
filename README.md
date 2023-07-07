# Hotel-Booking-Analysis
## 📖 Introduction

Analyzing the data of Hotel Booking. This data set contains booking information for a city hotel and a resort hotel and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things. All personally identifying information has been removed from the data.

We will perform exploratory data analysis with Python to get insight from the data.

Have you ever wondered when the best time of year to book a hotel room is? Or the optimal length of stay in order to get the best daily rate? What if you wanted to predict whether or not a hotel was likely to receive a disproportionately high number of special requests? This hotel booking dataset can help us explore those questions!


Dataset contains the following features:

1) hotel
2) is_canceled
3) lead_time
4) arrival_date_year
5) arrival_date_month
6) arrival_date_week_number
7) arrival_date_day_of_month
8) stays_in_weekend_nights
9) stays_in_week_nights
10) adults
11) children
12) babies
13) meal
14) country
15) market_segment
16) distribution_channel
17) is_repeated_guest
18) previous_cancellations
19) previous_bookings_not_canceled
20) reserved_room_type
21) assigned_room_type
22) booking_changes
23) deposit_type
24) agent
25) company
26) days_in_waiting_list
27) customer_type
28) adr
29) required_car_parking_spaces
30) total_of_special_requests
31) reservation_status
32) reservation_status_date


We have used Python 3 for its following packages:

1. Pandas
2. Matplotlib
3. Seaborn
4. Sklearn

## 📖 Conclusion


*   Here adr(average daily rate) is correlated with no_of_people. It simply indicates that more revenue is generated when the number of people increases.

*   Then, lead time and number of stays are correlated indicating that people take longer stay in hotels when booking is done more before then they arrive to stay.

*   The percentage of city hotels is 66.45% while the percentage of resort hotels is 33.55% is used to stay.


*   August is the month or we can say that the time of the year in which hotel booking is at its peak. And January is the month in which hotel bookings are the least.

*   According to the given data set the optimal length or favorable time of stay is less than 1 day for weekends and 2 days for weekdays.

*   Year 2016 is the highest booking year with a total booking of 56,707 then booking decreased to 40,687.

*   Most of the guests came from European countries, with most no. of the guests coming from Portugal. 

*   Mostly people stay 1 to 4 days. Generally, people go for City Hotels for staying short periods of time but for longer periods of stay people prefer Resort Hotel.
