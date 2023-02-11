# msia420PA_project

## Week1 Update

### Completed goals:
Research dataset
Define business problem
Explore the dataset

### Dataset: Hotel Reservations Dataset
Link to the dataset: https://www.kaggle.com/datasets/ahsan81/hotel-reservations-classification-dataset

### Business problem
Guest room scheduling is a key area in maintaining hotel operation efficiency. When a customer cancels their reservation unexpectedly, the hotel needs to spend extra effort in staff planning and extra cost on maintaining vacant rooms. A predictive model is built to help hotel owners understand whether a customer would cancel their reservation.

### Dataset Description:
The dataset consists of 36275 unique hotel booking records and 19 columns. The booking_status column will be the predicted variable of the model. 

**Column Name/Explanation**
- Booking_ID: unique identifier of each booking
- No_of_adults: Number of adults
- No_of_childre: Number of Children
- no_of_weekend_night: Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel
- no_of_week_nights: Number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel
- type_of_meal_plan: Type of meal plan booked by the customer
- required_car_parking_space: Does the customer require a car parking space?
- room_type_reserved: Type of room reserved by the customer
- lead_time: Number of days between the date of booking and the arrival date
- arrival_year: Year of arrival date
- arrival_month: Month of arrival date
- arrival_date: Date of the month
- market_segment_type: Market segment designation
- repeated_guest: Is the customer a repeated guest?
- no_of_previous_cancellations: Number of previous bookings that were canceled by the customer prior to the current booking
- no_of_previous_bookings_not_canceled: Number of previous bookings not canceled by the customer prior to the current booking
- avg_price_per_room: Average price per day of the reservation; prices of the rooms are dynamic. (in euros)
- no_of_special_requests: Total number of special requests made by the customer (e.g. high floor, view from the room, etc)
- booking_status: Flag indicating if the booking was canceled or not.

### Plan for next update:
- Start EDA of the dataset
- Start benchmark model


## Week3 Update
### Completed goals:
- Implememented EDA on the data set in terms of variables distributions, correlations, and inspecting outliers. 
- Compared datasets with and without outliers.
- One hot Encoding on categorical variables. 
Note book for week3: 

### Plan for next update:
- Continue with feature engineering
- Build a benchmark model
- Compare models with and without outiers. 
