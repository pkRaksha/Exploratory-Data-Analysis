# Exploratory-Data-Analysis
Hotel Booking analysis- EDA

Link to Dataset:https://drive.google.com/file/d/1C9AxF9fcVzMw0Bgs0NaRrNML2WwX1Ehm/view

Video Link :

Collab Link :https://colab.research.google.com/drive/1yVmb1C3GT012ukZTNYd_ZxpSHN5nix8f#scrollTo=Fjb1IsQkh3yE

Project Summary:
Objective : This project aims to analyze the pattern in hotel booking, and cancelations made to draw useful insights to impact business in a positive way.
Based on the given dataset it is evident that the hotel booking analysis data consists of various insights related to the number of bookings made by a different set of customers from various market segments. The length of their stay.The preferred meal types and the room types.

The booking cancelation gives us a place to start data-driven decisions to reduce the number of cancellations. For the business, providing the option to cancel a booking potentially generates more demand and helps to anticipate occupancy. The customer, they have more confidence to book However, the cost borne by the business due to cancellations are unutilized capacity and discounted room prices, leading to reduced profits. Hotels also bear an additional marketing cost to generate publicity.

The distribution channels used by the hotel to attract customers also add up to the additional marketing costs. The average daily rates for an occupied room help us determine if the hotel is running or profit or loss over some time. Different countries and their bookings made in each hotel type could also be observed Thus answering the question of which is the country which makes the most bookings. Increasing ads and discounts for people from countries who book less could increase our chances of getting more guests over the year. It is of great importance to observe the surge in bookings over a period of time each year and thus advertising more to attract more customers. The deposit type is also major in making a booking. For customers, it makes it easy to book a hotel on the fly and pay later. But for business, it might be a cause for cancelation too. Analysis needs to be done on the type of deposit done by various market segments. The special request gives an idea of the customer's expectations over their stay that isn't mentioned by the hotel. Based on the number of special requests we could improve the quality of stay for a customer.

This project is completely focused on building our analysis to help a business grow by doing the below major types of analysis:

Number of Cancelations and the factors which lead to the increase thus impacting the business negatively
The average length of stay of a customer is an important KPI to determine the average daily rates for the rooms occupied
The total number of bookings made over a period of time when there is a sudden surge/drop in the number of bookings caused to various factors helps us get a picture of the timeline when the hotel has booming guests and the reason for the drop
The preferred room types help us to increase the ADR by making those rooms more available.
The meal type is also vital for the business to attract customers by giving complementary or discounted prices on the most preferred meal.
Dataset:
hotel :Name of hotel (City or Resort Hotel)

is_canceled : 1 denotes the booking was canceled and 0 denotes booking was not canceled.

lead_time : time period (in days)between the actual date of booking and arrival date .

arrival_date_year : The year the guest arrived to hotel

arrival_date_month : The month corresponding to year the guest arrived.

arrival_date_week_number : The week number corresponding to the year the guest arrived

arrival_date_day_of_month: The day corresponding to the month the guest arrived

stays_in_weekend_nights : number of nights stayed during a weekend

stays_in_week_nights: number of nights stayed during a weekday

adults : number of adults stayed

children: number of children stayed

babies : number of babies stayed

meal: Type of meal opted by the guest BB: Bed & Breakfast HB: Half Board (Breakfast and Dinner normally) FB: Full Board (Beakfast, Lunch and Dinner) SC: Self Catering: The guest can prepare in kitchen prices will not be included.

country: The list of ISO3 country codes corresponding to the guest country are given.

market_segment : Types of market segment the guest belongs to

distribution_channel: Channel through which the bookings are made by each guest

is_repeated_guest: Whether the customer has made any booking before(0 for No and 1 for Yes)

previous_cancellations: Number of cancelation made by the guest during previous bookings

previous_bookings_not_canceled: Number of bookings not canceled by the guest.

reserved_room_type: Room type reserved by a guest.

assigned_room_type: Room type assigned to the guest.

booking_changes: No. of booking changes done by guest

deposit_type: Type of deposit at the time of making a booking (No deposit/ Refundable/ No refund)

agent: Id of agent for booking

company: Id of the company making a booking

days_in_waiting_list: No. of days on waiting list.

customer_type: Type of customer(Transient, Group, etc.)

adr :average rate per occupied room. (ADR = room revenue / number of rooms sold (occupied)

required_car_parking_spaces: No. of car parking asked in booking

total_of_special_requests: total no. of special request.

reservation_status: Whether a customer has checked out or canceled,or not showed

reservation_status_date: Date of making the reservation

Total number of rows in data: 119390
Total number of columns: 32

Business Objective:

Based on all the observations made lets conclude that to run a hotel business successfully there are certain majore aspects to be focused :

The occupancy in city and resort hotel is seasonal based on the trends show in the above chart . The hotel owners should avoid any bottlenecks during the peak times and also roll out offers during the off -peak times to increase the revenue
The cancellation rates are higher by the transient customers who book through travel agents .* The period of lead time can be made to less than 100 days to prevent the cancellations .
The managements can give the bed breakfast as complimentary since its the most preferred meal.
Portugal seems to have highest cancellation the management could focus more on countries like France, Spain, United Kingdom or United States which has moderate amount of customers with few cancellation.
The deposit type for booking through travel agents could add an extra charge on cancellatiwith its done after 10 days on to prevent the customers to make bookings and cancel later leading to a negative impact in business. The money used for ads and marketing goes into vain .
The aviation segement gives a stable adr .The management can focus on the aviation segment . While further improving the Direct and online TA segements


Conclusion:

Based on the Univariate analysis the conslusions are :


The Resort hotel have fewer cancelations .
The most preferred meal by the guest is bed breakfast.
Most number of bookings are made by agaent 9.

The Bi variate and multi variate analysis conclusions are :

The online TA has highest number of bookings and cancellations when compared to direct and offline TA/TO are more stable . The bookings made through the later are least likely to get cancelled .
The adr generated by different market segments shows that the aviation market segment has a more proportioned adr . While the Direct and Online TA have higher ADR.
The city vs Resort occupancy is shows a seasonal trend with highest occupancy over the months of August, July and May during each year . The resort hotel are occupied more . The bookings made in city hotels are high but the resort hotel are more stable .
Portugal seems to have the highest cancellation rate The countires like France Australia and United kingdome and United states have stable cancellations .
The average length of stay is very high in resort hotels
The transient customers prefer weekdays and make more bookings during this period.
The Most prefeered room type is A and its mostly occupied by Transient customers.
The deposit transient customers with no deposit type are more likely to cancel
The cancellations spiked during july 2015 The other periods it looks moderate in both resort and city hotel .
The lead time less than 100 days could be made to prevent the cancellation since the lead time between 200 to 400 have very high cancellation rates
The waiting time is negatively correlated with repeated guest .More the waiting time the customer might cancel . The customers who never cancelled previously are more likely to check out. Hence the Resort hotel has more stability in functioning successfully.
