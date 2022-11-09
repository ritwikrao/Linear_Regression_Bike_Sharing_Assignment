# Project Name
> Linear Regression on Bike Sharing


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands
- Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
The number of people who avail the service depeneds on 6 factors namely - Yr, Temp, Windspeed, Season_4 (Winter), Mnth_9 (September) and Weathersit_3 (Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds)
  Year - As we progress through years, the footfall of people is also increasing
  Temp - Temperature is positively correlated, implying an increase in temperature will increase the number of people utilising the service
  Windspeed - Windspeed is negatively correlated, implying that an increase in windspeed reduces the footfall of people utilising the service
  Season - Winter season is positively correlated with the count of people utilising the service. A unit increase in winter will increase the usage of bikes by 0.100551 units
  Month - September month has a positive correlation with the footfall is people
  Weather - This has a negative correlation and as the weather gets worse the number of people using the service comes down

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python 3.9.12
- Pandas 1.4.2
- NumPy - 1.21.5
- Seaborn - 0.11.2
- Statsmodel - 0.13.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by @ritwikrao - feel free to contact me at ritwik199717@gmail.com!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
