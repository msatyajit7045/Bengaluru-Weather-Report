# Bengaluru-Weather-Report
This rainfall prediction project which is a data-driven initiative that aims to forecast the amount of rainfall that can be expected in Bangalore. The data for this project was collected from Open Meteo in a time range of 18/02/2020 to 18/02/2023.

I developed two models - a linear regression model and a gradient boost regressor. The linear regression model achieved an R2 score of 0.85, indicating that it could explain 85% of the variance in the rainfall data. However, the gradient boost regressor outperformed the linear regression model, achieving an R2 score of 0.95, which suggests that it could explain 95% of the variance in the rainfall data.

Overall, the project successfully developed a prediction model that can forecast rainfall with a high degree of accuracy. The results suggest that the gradient boost regressor is the most effective model for this particular dataset, and could potentially be used to inform planning and decision-making in a range of industries, such as agriculture, disaster management, and urban planning.

The Dataset contains the following columns.
● time

● weathercode

● temperature_2m_mean (°C)

● apparent_temperature_mean (°C)

● shortwave_radiation_sum (MJ/m²)

● precipitation_sum (mm)

● rain_sum (mm)

● precipitation_hours (h)

● windspeed_10m_max (km/h)

● windgusts_10m_max (km/h)
