# Model for Bike Rental using Linear Regression
> Predicting the No. of users per day using Linear Regression model


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Univariate :
  - We can conclude that the most bike rentals happens in Autumn and the least in Spring
  - The Total Count does not vary much with the day of week.
  - We can conclude that the Count is the highest when the weather is Clear i.e. Clear, Few clouds, Partly cloudy, Partly cloudy and neglegible when the day is rainy i.e. Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds.
  - Not much difference in the average value count of bike rentals on working day
  - The holiday column is mostly zero so not much can be inferred , lets check if there is an increase in bike rentals during holidays. There is not much difference between the avg of cnt with respect to holiday , so it should be safe to drop holiday 
- Bivariate :
  - 9th Month is the most humid and 6th the least
  - The mean tempetrature is least in the 1st month and most in the 7th
  - There is not much change in the humidity for different seasons
- R-squared:                       0.779
- Adj. R-squared:                  0.775

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- scikit learn 
- numpy 
- pandas 
- matplotlib
- seaborn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by Upgrad.


## Contact
Created by [@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
