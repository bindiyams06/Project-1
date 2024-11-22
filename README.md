# Event Based Management
This project involved 5 fact tables - BlueCard(Event), Contracts, Presentors, Venue and Artist
The process includes entry point where presentor becomes a BlueCard(Event) holder once the team signs a contract for the event that includes the venue details and the artists who will be perfoming at the event.

# Forecast Contract revenue 
Utilized ARIMA for revenue prediction as it's better suited for time series model. Forecasted the revenue for next 3 months based on the historical data of 11 years.
Calculated metrics MSE, MAPE and RMSE manually as well as using auto_arima(auto-fit model) to compare the results
