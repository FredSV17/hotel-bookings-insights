# Hotel Booking Insights

This project aims to analyze and derive insights from a dataset of hotel bookings. By exploring various aspects of the data, such as booking patterns, customer 
demographics, and seasonal trends, we can uncover valuable information that can help improve hotel management and marketing strategies.

The dataset used for this project contains 119390 rows containing observations from city hotel and resort hotel bookings, between the 1st of July 2015 and 31st of August 2017.

## Dataset Columns

The dataset contains the following columns:

- **hotel**: Type of hotel (City Hotel or Resort Hotel).
- **is_canceled**: Indicates if the booking was canceled (1) or not (0).
- **lead_time**: Number of days between the booking date and the arrival date.
- **arrival_date_year**: Year of arrival date.
- **arrival_date_month**: Month of arrival date.
- **arrival_date_week_number**: Week number of year for arrival date.
- **arrival_date_day_of_month**: Day of arrival date.
- **stays_in_weekend_nights**: Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay.
- **stays_in_week_nights**: Number of week nights (Monday to Friday) the guest stayed or booked to stay.
- **adults**: Number of adults.
- **children**: Number of children.
- **babies**: Number of babies.
- **meal**: Type of meal booked.
- **country**: Country of origin.
- **market_segment**: Market segment designation.
- **distribution_channel**: Booking distribution channel.
- **is_repeated_guest**: Indicates if the booking is from a repeated guest (1) or not (0).
- **previous_cancellations**: Number of previous bookings that were canceled by the customer prior to the current booking.
- **previous_bookings_not_canceled**: Number of previous bookings not canceled by the customer prior to the current booking.
- **reserved_room_type**: Code of room type reserved.
- **assigned_room_type**: Code for the type of room assigned to the booking.
- **booking_changes**: Number of changes/amendments made to the booking.
- **deposit_type**: Type of deposit made for the booking.
- **agent**: ID of the travel agency that made the booking.
- **company**: ID of the company/entity that made the booking.
- **days_in_waiting_list**: Number of days the booking was on the waiting list.
- **customer_type**: Type of customer (e.g., transient, contract, group).
- **adr**: Average Daily Rate, as defined by dividing the sum of all lodging transactions by the total number of staying nights.
- **required_car_parking_spaces**: Number of car parking spaces required by the customer.
- **total_of_special_requests**: Number of special requests made by the customer (e.g., extra bed, high floor).
- **reservation_status**: Reservation status (e.g., canceled, check-out).
- **reservation_status_date**: Date when the last status was set.


Dataset link: [Hotel Booking Dataset](https://www.kaggle.com/datasets/mojtaba142/hotel-booking)