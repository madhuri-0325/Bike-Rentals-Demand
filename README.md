# Bike-Rentals-Demand
The goal is to generate actionable insights for optimizing bike distribution and improving service levels across the bike-sharing network.¶
<br>
Insights that are drawn from the data source:
<br>
The demand for bike rental increases as the temperature increases and reaches a peak of around 25-30 degrees Celsius. Humidity and windspeed have negative impacts on rentals, and adjusted temp shows the same impact as temp. Rentals increased from 2011 to 2012 which shows the growing popularity of rentals over time. Irrespective of a holiday or working day the demand for rentals is the same. The rentals are low on 1st season compared to other seasons. The most favorable weather conditions for rental are 1 and 2. The rentals are lowest in the early and late months of the year which means bikers prefer warmer months for rental than colder months. The demand for bike rental increases from morning 6AM and peaks at around 8-9 AM, after that there is a drop in demand till around 3PM and again increases in the evening and shows a peak at around 5-6 PM and after that rentals are steadily decreasing. so the rush hours for rentals will be morning around 8-9 AM and evening around 5-6 PM. On working days, the demand for bike rentals is very high at 6-9 AM and evening 5-10 PM.

<br>
coming to ML models the Random Forest Regressor is performing better than the Decision Tree Regressor based on the evaluation metrics (lower MSE, MAE, and higher R²). so the Random Forest Regressor will be the preferred model for predicting bike rentals.
