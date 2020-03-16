# surfs_up
weather_analysis_app

## Project Overview
Supported business decision about opening ice cream shop in Oahu, Hawaii by providing statistical analysis of the local weather data. 
Conducted data analysis to determine potential business risk for ice cream shop based weather variability.

## Resources

-	Software: Python 3.7.6 with panda and sqlite packages, Jupiter Notebook
- hawaii.sqlite weather data basis


## Challenge overview
Conducted statistical analysis of the weather (temperature and rain precipitation) in Oahu, Hawaii, during two periods June and December over 8 years of data. Provided key values such as, average and statistical distribution of temperature and precipitation for both months. Conducted additional analysis of the weather trends over the period of 8 years for June and December. The analysis of the wether during season (June) and off the season (December is essential to predict potential income variation and busins impact.   


## Results report 

The statistical analysis was conducted on weather data from June and December over 6 years from all Oahu stations. Key statistical data are summarized in Table 1. The additional analysis includes: (1) precipitation to temperature comparison based on yearly trends, (2) season to season comparison based on yearly trends for June and December, (3) Box plot analysis of temperature and rain, Table 2.

The average temperatures in Oahu are: 74.94F in June and 71.04F in December, and are close to median: 75.00C in June and 71.00C in December. The temperature quartile range is 4F in June and 5F in December which indicates to low temperature variations. The temperature yearly trend analysis showed low year to year temperature variation for June. For December there are years with occasionally average temperature (73.4F) but not exceptionally cold years. Looking at box plots of temperature distributions (Fig), there is clear difference between June and December temperatures. However the difference is only ~5-6F at maximum, thus the temperature is not potential risk for business impact.

The precipitation in Oahu in June is 0.14mm average and 0.02mm median which suggests infrequent but sometimes heavy rain. In December the precipitation is only ~50% larger: 0.22mm average and 0.03mm median. Based on additional analysis of the precipitation trends the there is only 1 out of 8 years significant precipitation increase in December compared to June (Fig). However at the same year,2010, June noted record low rain precipitation. The low income in December would be balanced by previously high in June. The box plot analysis (FIG) shows that even though median rain precipitation for December is larger within range of precipitation in June, i.e. no extreme rains in December. Thus rani precipitation is within acceptable risk.

The set of average rain precipitation to temperature over the years allows to grasp the idea about potential income. For low precipitation and high temperature income is higher, compared to high precipitation and high temperature or low precipitation and low temperature. For June, out of 8 years, 6 consecutive years reported temperature higher than average 75F, with yearly precipitation below average 0.13mm. One year with low temperature 74F had extremally low precipitation 0.04mm. One year had precipitation 0.21mm, comparable to December.  December has 1 out of 8 years with extremally high precipitation 0.45mm combined with low average temperature 70F.

Investment in ice cream shop on Oahu has low risk due to the weather. Even though the average rain precipitation in December is 50% larger than in June the impact of the in December can be mitigated with good weather in June
