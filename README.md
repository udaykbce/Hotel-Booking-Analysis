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

1) City hotels are the most preferred hotel type by the guests. We can say the City Hotel is the busiest hotel.
2) 27.5 % of bookings were got canceled out of all the bookings.
3) Only 3.9 % of people have revisited the hotels. The rest 96.1 % were new guests. Thus retention rate is low.
4) The percentage of 0 changes made in the booking was more than 82 %. The percentage of Single changes made was about 10%.
5) Most of the customers (91.6%) do not require car parking spaces.
6) 79.1 % of bookings were made through TA/TO (travel agents/Tour operators).
7) BB( Bed & Breakfast) is the most preferred type of meal by the guests.
8) Maximum number of guests was from Portugal, i.e. more than 25000 guests.
9) Booking cancellation rate is high for City hotels which is almost 30 %.
10) Waiting time period for City hotels is high as compared to resort hotels. That means city hotels are much busier than Resort hotels.
