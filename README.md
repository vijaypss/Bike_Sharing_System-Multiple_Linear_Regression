# Bike Sharing System - Multiple Linear Regression
> Python Code to generate Multiple Linear Regression Model to predict the Demand for Shared Bikes.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
 You work for a Consulting Company for which the Bike Sharing Service firm have given contract to understand the factors on which the demand for these shared bikes depends. The Company is provided with various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.

 With the provided data, the company is required to model the demand for shared bikes with the available independent variables. Therefore, derive the following from it:

 - Which variables are significant in predicting the demand for shared bikes.
 - How well those variables describe the bike demands¶
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The Equation produced by the linear-regression model to predict the total number of users is as:</br>
 TotalUsers = 0.246 - 0.249 x lightSnow - 0.180 x windspeed - 0.123 x hum - 0.074 x Spring - 0.064 x holiday - 0.059 X Mist</br> + 0.019 X workingday + 0.043 X Summer + 0.049 X weekday + 0.090 X Winter + 0.232 X yr + 0.493 X temp
- The User Demand for the Bike Sharing Service is positively affected by workingday, weekday, summer, winter and temp variables.`
- The User Demand for the Bike Sharing Service is negatively affected by lightSnow, windspeed, Spring, holiday and Mist variables.
- The model cannot be expressed as exact model and it can also be improved.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Jupyter Notebook - version 6.4.5
- Python - version 3.9.7
- Pandas - version 1.3.4
- Numpy - version 1.20.3
- Matplotlib - version 3.4.3
- Seaborn - version 0.11.2
- Scikit-learn - version 0.24.2
- Scipy - version 1.7.1

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project is the case study from the Upgrad. Thankful to the Upgrad & IIIT, Bangalore for providing the necessary knowledge, opportunity & support.
- The References are from various internet sources and documents.


## Contact
Created by [@vijaypss] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->