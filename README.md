<h1>Table of Contents<span class="tocSkip"></span></h1>
<div class="toc"><ul class="toc-item"><li><span><a href="#Exploring-Climate-Change" data-toc-modified-id="Exploring-Climate-Change-1">Exploring Climate Change</a></span><ul class="toc-item"><li><span><a href="#About-This-Project" data-toc-modified-id="About-This-Project-1.1">About This Project</a></span><ul class="toc-item"><li><span><a href="#Contributors" data-toc-modified-id="Contributors-1.1.1">Contributors</a></span></li></ul></li><li><span><a href="#Why-Climate-Change?" data-toc-modified-id="Why-Climate-Change?-1.2">Why Climate Change?</a></span></li><li><span><a href="#Problem-Definition" data-toc-modified-id="Problem-Definition-1.3">Problem Definition</a></span></li><li><span><a href="#Models-Used" data-toc-modified-id="Models-Used-1.4">Models Used</a></span></li><li><span><a href="#Content-Flow" data-toc-modified-id="Content-Flow-1.5">Content Flow</a></span></li><li><span><a href="#Conclusion" data-toc-modified-id="Conclusion-1.6">Conclusion</a></span></li><li><span><a href="#Insights-Gained-From-This-Project" data-toc-modified-id="Insights-Gained-From-This-Project-1.7">Insights Gained From This Project</a></span></li><li><span><a href="#References" data-toc-modified-id="References-1.8">References</a></span></li></ul></li></ul></div>

# Exploring Climate Change

Climate change refers to long-term shifts in temperatures and weather patterns. Such shifts can be natural, due to changes in the sun’s activity or large volcanic eruptions. But since the 1800s, human activities have been the main driver of climate change, primarily due to the burning of fossil fuels like coal, oil and gas.

Burning fossil fuels generates greenhouse gas emissions that act like a blanket wrapped around the Earth, trapping the sun’s heat and raising temperatures.

The main greenhouse gases that are causing climate change include carbon dioxide and methane. These come from using gasoline for driving a car or coal for heating a building, for example. Clearing land and cutting down forests can also release carbon dioxide. Agriculture, oil and gas operations are major sources of methane emissions. Energy, industry, transport, buildings, agriculture and land use are among the main sectors causing greenhouse gases.

## About This Project
This Mini-Project serves as the final graded piece of work for SC1015 (Introduction to Data Science and Artificial Intelligence). The aim of this project is to utilise supervised learning techniques to tackle a chosen problem.

### Contributors


## Why Climate Change?
* “In 2021, the global mean temperature was about 1.1°C above the pre-industrial level (from 1850 to 1900).The years from 2015 to 2021 were the seven warmest on record.” - United Nations 2022

Global warming is an issue that affects our planet in several ways:

- Rising Temperatures
- Health impacts : Increased heat leads to dehydration, heat exhaustion, and heatstroke.
- Melting of glaciers and ice caps
- Ocean acidification
- Increased frequency of natural disasters



## Problem Definition
* Global Warming has become a major issue especially over recent years, with temperature rising at an alarming rate. Therefore, our team finds it important to be able to project future temperatures of countries as well as find the predictors that have the most effect on rising temperature. 
<br>
* Are we able to predict the temperature of the land surface area for each country 10 years from now (2023) based on the country's GHG emissions?
<br>

* What is the most optimal model to takle this time-series forcasting?
<br>
* Which predictor has the most effect on rising temperature?

## Models Used
* SARIMA
* Prophet

## Content Flow
The source code for this project is sectioned into five different files for ease of viewing the source code. For the best experience of this project, please view the files in the following order:
1. Data Preparation
2. Data Visualisation
3. Data Resampling and Splitting
4. ARIMA
5. Prophet

## Conclusion
* Both models show an accurate forecast/prediction of a country’s temperature as shown in the graphs plotted.

-The RMSE value for SARIMA = 1.37 degrees Celsius.

-The RMSE value for Prophet = 1.117 degree Celsius.

-RMSE(Prophet)<RMSE(SARIMA)

-Hence the Prophet model is more accurate.

* Checking on our predictors

-Nitrous oxide, co2 including luc and methane have a positive relation to rising temperature. Hence these factors should be addressed and minimised as to slow down the rate of increasing temperature.


## Insights Gained From This Project
* Important to select relevant columns.

-Some datasets can be too excessive and would be difficult to have a clear focus, such as the one from https://github.com/owid/co2-data

* Important to look out for outliers. 

-Such as the data in Hong Kong and Taiwan where there lacks of data and hence removed from the dataframe.

* Important to find a suitable range that suits to all datasets.

-To ensure that the data are all on the same scale and are comparable, creating a more accurate time series forecast.


## References
* Artley, B. (2022, April 27). Time Series Forecasting with Arima,Sarima and Sarimax. Towards Data Science. Retrieved from: 
https://towardsdatascience.com/time-series-forecasting-with-arima-sarima-and-sarimax-ee61099e78f6

* Cheong, J. (2019, May 13). Four ways to quantify synchrony between time series data. Towards Data Science. Retrieved from: https://towardsdatascience.com/four-ways-to-quantify-synchrony-between-time-series-data-b99136c4a9c9

* Choudhary, A. (2022, June 23). Time Series Forecasting with Facebook Prophet. Analytics Vidya. Retrieved from:
https://www.analyticsvidhya.com/blog/2018/05/generate-accurate-forecasts-facebook-prophet-python-r/

* Earth, B., Sissener, K. (2017). GlobalLandTemperaturesByCountry dataset. Kaggle. Retrieved from:
https://www.kaggle.com/datasets/berkeleyearth/climate-change-earth-surface-temperature-data?select=GlobalLandTemperaturesByCountry.csv

* Ng, J.P.L. (2022, February 19). Heatmap For Correlation Matrix & Confusion Matrix | Extra Tips On Machine Learning. Medium. Retrieved from: https://medium.com/mlearning-ai/heatmap-for-correlation-matrix-confusion-matrix-extra-tips-on-machine-learning-b0377cee31c2

* Our World in Data. (2023, January). Co2 dataset. GitHub. Retrieved from: https://github.com/owid/co2-data

* United Nations. (n.d.). United Nations Sustainable Development Goals Report 2022. Retrieved from:
https://www.un.org/sustainabledevelopment/climate-change/#:~:text=Facts%20and%20figures-,In%202021%2C%20the%20global%20mean%20temperature%20was%20about%201.1%C2%B0,of%20the%20next%20five%20years.

* United Nations. (n.d.). What is Climate Change. Retrieved from: https://www.un.org/en/climatechange/what-is-climate-change


