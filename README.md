# E-Commerce Financial Analysis

<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name=" Rental-Market-Data-San-Fran"></a>
<img src="https://github.com/Nievz/e_commerce_financial_analysis/blob/main/Images/Market.jpg" alt="Logo" width="1000" height="450">

<!-- ABOUT THE PROJECT -->
## About The Project

  <p align="center"> 
    The purpose of this analysis is to look at MercadoLibre, Latin America's most popular e-commerce site with over 200 million users. We are analyzing the company's financial and user data in order to help it grow. We look into the ability to forecast search traffic and translate prediction models into the ability to trade stocks successfully.
  </p>

  <p align="center" style="display: flex;" >
<img src="https://github.com/Nievz/e_commerce_financial_analysis/blob/main/Images/market.png" alt="Logo" width="50" height="50">  
<img src="https://img.shields.io/npm/l/express" />
<img alt="GitHub code size in bytes" src="https://img.shields.io/github/languages/code-size/tyleradammartinez/SIG-Dashboard-Application" />
    <img src="https://github.com/Nievz/e_commerce_financial_analysis/blob/main/Images/market.png" alt="Logo" width="50" height="50"> 
</p>


## The high-level steps for this Analysis are as follows:
`We Find Unusual Patterns in Hourly Google Search Traffic` <br>
`We Mine the Search Traffic Data for Seasonality`<br>
`We Relate the Search Traffic to Stock Price Patterns` <br>
`We Create a Time Series Model by Using Prophet` <br>
`We Forecast the Revenue by Using Time Series Models` <br>
    
## Required Python Required Libraries and Dependencies

### CALCULATIONS
`pip install pystan` <br>
`pip install prophet`<br>
`pip install hvplot` <br>
`pip install holoviews` <br>

`import pandas as pd` <br>
`import holoviews as hv`<br>
`from prophet import Prophet` <br>
`import hvplot.pandas` <br>
`import datetime as dt` <br>
`%matplotlib inline` <br>
`import warnings` <br>
`warnings.filterwarnings('ignore')` <br>

<!-- GETTING STARTED -->
## Data and Research Design

### Search traffic by Hour of The Day and Day of the Week

  <p align="center">
  </p>

<img src="https://github.com/Nievz/e_commerce_financial_analysis/blob/main/Images/HeatMap.png" width="1000" height="500"> 

### Stock Volatility

  <p align="center">
  </p>

<img src="https://github.com/Nievz/e_commerce_financial_analysis/blob/main/Images/stock volatility.png" width="1000" height="500"> 

### Stock Variable Close

  <p align="center">
  </p>

<img src="https://github.com/Nievz/e_commerce_financial_analysis/blob/main/Images/variable close.png" width="1000" height="500">

### Variable Search Treands

  <p align="center">
  </p>

<img src="https://github.com/Nievz/e_commerce_financial_analysis/blob/main/Images/variable search treands.png" width="1000" height="500">

### Prophet Predictions for the Mercado Trends Data

  <p align="center">
  </p>

<img src="https://github.com/Nievz/e_commerce_financial_analysis/blob/main/Images/model.png" width="1000" height="500">

  <p align="center">
  </p>

<img src="https://github.com/Nievz/e_commerce_financial_analysis/blob/main/Images/prophet model.png" width="1000" height="500"> 

<p align="center">
  </p>

### Model Mercado Trends by Years

  <p align="center">
  </p>

<img src="https://github.com/Nievz/e_commerce_financial_analysis/blob/main/Images/treand by year.png" width="1000" height="500"> 

<p align="center">
  </p>

 ### Model Mercado Trends by Weeks

  <p align="center">
  </p>

<img src="https://github.com/Nievz/e_commerce_financial_analysis/blob/main/Images/treand by week.png" width="1000" height="500"> 

<p align="center">
  </p>

### Model Mercado Trends by Year

  <p align="center">
  </p>

<img src="https://github.com/Nievz/e_commerce_financial_analysis/blob/main/Images/treand by y.png" width="1000" height="500"> 

<p align="center">
  </p>
  
### Model Mercado Trends Daily

  <p align="center">
  </p>

<img src="https://github.com/Nievz/e_commerce_financial_analysis/blob/main/Images/treand daily.png" width="1000" height="500"> 

<p align="center">
  </p>

## Conclusion

  <p align="center">
    
  ## Question: Based on the forecast information generated above, produce a sales forecast for the finance division, giving them a number for expected total sales next quarter. Include best and worst case scenarios, to better help the finance team plan?
        
Answer: According to our analysis, the results of forecasting and applying the prediction to the data which includes the timeframe between 2020-07-01 and 2020-09-30, led us to the conclusion that the prediction would be closest to 888 million USD in the case of worst case possible scenario, 970 million USD in the case of the most likely scenario, and 1051.5 in the case of the best possible scenario. 


  </p>

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [https://bootcampspot.instructure.com/courses/3828/assignments/57439?module_item_id=1009931]()
* [https://facebook.github.io/prophet/docs/quick_start.html]()
* [https://hvplot.holoviz.org/]()
* [https://www.pexels.com/photo/assorted-fruits-and-vegetables-in-baskets-for-sale-in-the-fruit-market-3043328/]()
* [https://www.flaticon.com/free-icon/market_11527109?term=market&page=1&position=39&origin=search&related_id=11527109]()
* [https://www.youtube.com/watch?v=j0eioK5edqg]()
* [https://github.com/othneildrew/Best-README-Template/blob/master/BLANK_README.md]()
  
  

