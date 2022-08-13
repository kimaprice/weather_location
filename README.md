# Analysis of weather at various latitudes
#### Kim Price
----
#### A random sample of over 500 cities in the world was gathered.  Weather data for 8/12/2022 was obtained for these cities using the Open Weather Map API.  The data points were analyzed to identify if any correlations exist in the various points of interest and the cities distance from the equator (latitude).

#### Weather Data (points of interest):
* Max Temperature (Degrees F)
* Humidity (%)
* Cloudiness (%)
* Wind Speed (mi/hr)

#### Summary of findings (also shown in file - next to corresponding plots)
* The maximum temperature decreases as you move away from the equator.
    * Evidence:
        * Negative slope on the regresssion line for the northern hemisphere.
        * Positive slope on the regression line for the southern hemisphere.
        * R scores for both northern and southern hemispheres is above .5.
* Humidity is not impacted by distance from the equator. 
    * Evidence:
        * Very small slope on the regresssion line for the northern hemisphere.
        * Very small no slope on the regression line for the southern hemisphere.
        * R scores for both northern and southern hemispheres is well below .5.
* Cloudiness is not impacted by distance from the equator. 
    * Evidence:
        * Very small slope on the regresssion line for the northern hemisphere.
        * Very small no slope on the regression line for the southern hemisphere.
        * R scores for both northern and southern hemispheres is well below .5.
* Wind Speed is not impacted by distance from the equator. 
    * Evidence:
        * Very small slope on the regresssion line for the northern hemisphere.
        * Very small no slope on the regression line for the southern hemisphere.
        * R scores for both northern and southern hemispheres is well below .5.
    
#### Limitiations
* This data is a snapshot in time covering only one day in August.  The data if gathered over a longer timespan or even if taken on a day during a different time of the year, may show different results.

#### My Recommended Vacation Destinations
----
##### Based on analysis of the weather on 8/12/2022, I have provided a recomendation of possible vacation locations (with hotel) meeting my 'ideal' weather criteria in VacationPy.
#### Criteria:
* Max temperature <= 80
* Min temperature >= 75
* Wind Speed < 7 mi/hr
* Cloudiness <= 50
* Humidity <= 75
