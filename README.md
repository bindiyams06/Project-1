# 📒Event Based Management
## Introduction:
Event management database is a dataset that holds details about events such as event name, date, venue details, artist details, contract details and its payments

## ⏳Process:
- The process begins when the presenter becomes a BlueCard(Event) holder, which occurs once the event team finalizes and signs a contract for the event. This contract outlines key details, including the venue information and the artists scheduled to perform at the event.
  
- The presenter, upon securing the signed contract, assumes responsibility for managing all aspects of the event from this point forward.

## 👩🏻‍💻Database:
- Entities:- Event, Artist, Contract, Presenter, Venue 
- Fact tables:- Event, Contract, ArtistEnrollType, Discounts 
- Dimensonal tables:- Artist, Veneue, Presenter, Event Type, ContractStatus 


## 🗓️Forecast Contract Revenue: 
**Data Collection and Prepartion:** Collected previous 10 years revenue based on the year 
**Forecasting model:** Utilized ARIMA for revenue prediction as it's better suited for time series model. Forecasted the revenue for next 3 months based on the historical data.
**Data Validation:** Calculated metrics MSE, MAPE and RMSE manually as well as using auto_arima(auto-fit model) to compare the results

## 🧰Tools:
Azure Machine Learning, Azure Database
