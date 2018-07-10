# Tableau CityBike

## Architecture:
- Consolidation, cleaning and transforming data using Alteryx.
- Data pulled from Jan 2017 to May 2018
- Storage in SQL Server.
- Extract data in tde for better performance
- Dashboards and sheets developed in Desktop Browser size (1000 * 800)

## Most important dashboards and views:

## Dashboard
- Answers most of the business questions required.
### Insights:
- The average miles ridden per trip is: 3.44 miles. (we assume average speed is 12 mph)
- In Apr-2017 we got the highest peak of growth in trips: 80%. In 2018, the number os trip are more stable, trend to growth.
- On winter season there is a normal decressing of trips. We can said due to adverse climate situation.
- Most of the riders populations are non-subscribers males.
- Most used stations are in the hearth of Manhattan and Wall Street.

## Seasons Peak Hour
- All seasons have the same peak hours: At morning from 8-9am, at night at 5-6pm. This means the main used of this bikes are for going to work. In winter there is a significative decrease because of the bad weather.

## Average trip Age
- We calculate age based on birth of year, however there is a lot of fake data, so this information in not accurate.
- However we can say, people at 16 have the longest average trip: 40min.There is a strange peak at 31 with an average of 24 minutes.
- And the rest of people in middle age have an average trip of 10-15minutes (short rides).
