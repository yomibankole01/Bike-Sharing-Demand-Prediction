# Seoul Bike Sharing Demand Prediction - Regression

## **Project Description**
This project aims to enhance the mobility and convenience of the public through bike-sharing programs in metropolitan areas. One of the main challenges is maintaining a consistent supply of bikes for rental. Bike-sharing systems are automated and enable people to rent and return bikes at various locations. The project focuses on utilizing historical data on factors such as temperature and time to predict the demand for the bike-sharing program in Seoul.

## **Dataset Description**
- The dataset provided contains 14 columns and 8760 rows and does not have any missing or duplicate values.
- The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.

<b>Attribute Information: </b>

* Date: year-month-day
* Rented Bike count: Count of bikes rented at each hour
* Hour: Hour of the day
* Temperature: Temperature in Celsius
* Humidity: %
* Windspeed: m/s
* Visibility: 10m
* Dew point temperature: Celsius
* Solar radiation: MJ/m2
* Rainfall: mm
* Snowfall: cm
* Seasons: Winter, Spring, Summer, Autumn
* Holiday: Holiday/No holiday
* Functional Day: NoFunc(Non Functional Hours), Fun(Functional hours)

## **All the Steps in Sequence**
- Step 1: Problem Statement
- Step 2: Know your Data
- Step 3: Understand your Variables
- Step 4: EDA
- Step 5: Data Cleaning
- Step 6: Feature Engineering
- Step 7: Model Building
- Step 8: Model Implementation
- Step 9: Conclusion

## **Conclusion:**
1. The majority of rentals are for daily commutes to workplaces and colleges. Therefore open additional stations near these landmarks to reach their primary customers.

2. We see 2 rental patterns across the day in bike rental count - first for a Working Day where the rental count is high at peak office hours (8 am and 5 pm) and the second for a Non-working day where the rental count is more or less uniform across the day with a peak at around noon.

3. Hour of the day: Bike rental count is mostly correlated with the time of the day. As indicated above, the count reaches a high point during peak hours on a working day and is mostly uniform during the day on a non-working day.
