# business_analytics
business_analytics in Yandex.Afisha

I studied :
How people use the product
When they start to buy
How much money each customer brings
When they pay off  

Step 1. Download the data and prepare it for analysis

Step 2. Make reports and calculate metrics:
Analysis of Market ( sales and products)

Step 3. Write a conclusion: advise marketing experts how much money to invest and where.
 Analysis of different sources and find the most profitables.

Description of the data
The visits table (server logs with data on website visits):
Uid — user's unique identifier
Device — user's device
Start Ts — session start date and time
End Ts — session end date and time
Source Id — identifier of the ad source the user came from
All dates in this table are in YYYY-MM-DD format.
The orders table (data on orders):
Uid — unique identifier of the user making an order
Buy Ts — order date and time
Revenue — Yandex.Afisha's revenue from the order
The costs table (data on marketing expenses):
source_id — ad source identifier
dt — date
costs — expenses on this ad source on this day
