# Project Name
> This project is model that looks at the demand for shared bikes with the available independent variables. It will be used by bike management rental company to understand how exactly the demands vary with different features. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
## General Information
- This model takes the data from a bike rental company that has 16 different variables. These variables are split between numerical 
and categorical. The bike rental company wants to know what independent variables affect bike rentals so they could maybe promote better
or be able to address supply chain needs. The dataset day.csv was given by the rental company. 

## Technologies Used
- Jupyter Notebook 6.5.4

## Conclusions
- Temperature (temp) - A coefficient value of .5687 indicated that a unit increase in temp variable increases the bike hire numbers by 0.5687 units.
- Weather Situation 3 (weathersit_3) - A coefficient value of -0.2541 indicated that a unit increase in Weathersit3 variable (Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds) compared to Weathersit1 (Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds)  decreases the bike hire numbers by .2541 units.
- Year (yr) - A coefficient value of .2337 indicated that a unit increase in yr variable increases the bike hire numbers by 0.2337 units.
-  season_4: - A coefficient value of .1275 indicated that a unit increase in season_4 variable (winter) compared to season_1(spring) increases the bike hire numbers by 0.1275 units.
- windspeed: - A coefficient value of -.1453 indicated that, a unit increase in windspeed variable decreases the bike hire numbers by 0.1453 units.
-As per our final Model, the top 3 predictor variables that influences the bike booking are:

   - Temperature (temp) - A coefficient value of .5687 indicated that a unit increase in temp variable increases the bike hire numbers by 0.5687 units.
   - Weather Situation 3 (weathersit_3) - A coefficient value of -0.2541 indicated that a unit increase in Weathersit3 variable (Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds) compared to Weathersit1 (Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds)  decreases the bike hire numbers by .2541 units.
   - Year (yr) - A coefficient value of .2337 indicated that a unit increase in yr variable increases the bike hire numbers by 0.2337 units.

So these 3 variables are the best to look at. 

You can also consider these variables: 


    season_4: - A coefficient value of .1275 indicated that a unit increase in season_4 variable (winter) compared to season_1(spring) increases the bike hire numbers by 0.1275 units.

    windspeed: - A coefficient value of -.1453 indicated that, a unit increase in windspeed variable decreases the bike hire numbers by 0.1453 units.

This model had an adjusted r2 value of .764

## Acknowledgements
-upGrad


