# Boom Bike Sharing Assignment
> A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues. They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

> Which variables are significant in predicting the demand for shared bikes.
> How well those variables describe the bike demands
> We are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.
> We have developed this case study as part of the Linear Regression Module for the Executive PG Programme in Machine Learning & AI - IIIT,Bangalore.



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues. They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands
- We have used day.csv as dataframe?

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- As per our final linear Model, the top 3 predictors that influences the bike booking are:

- Temperature (temp) -

    - A coefficient value of ‘0.49’ tells that a unit increase in temp increases the bike counts by 0.49 units.
- Year (yr)

    - A coefficient value of ‘0.24’ tells that a unit increase in year increases the bike counts by 0.24 units.
- Weather Situation (Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds) -

    - A coefficient value of ‘-0.29’ tells that a unit increase in weathersit_Light Snow decreases the bike counts by 0.29 units.
So It is advice to focus above variables utmost preferences while planning to achive maximum bookings

- The next best predictors that can also be considered are -

- weekday_Sun:
    - A coefficient value of ‘0.06’ tells that a unit increase in season_winter increases the bike counts by 0.06 units.
- season_spring:
    - A coefficient value of ‘-0.11’ tells that a unit increase in season_spring decreases the bike counts by 0.11 units.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas library - version 1.3.4
- numpy library - version 1.21.4
- matplotlib library - version 3.5.0
- seaborn library - version 0.11.2
- statsmodels
- sklearn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was based on Linear Regression Module for the Executive PG Programme in Machine Learning & AI - IIIT,Bangalore.


## Contributors
- <a href="https://github.com/pradeepksharma22/">Pradeep Kumar Sharma</a>


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
