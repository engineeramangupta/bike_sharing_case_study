# Project Name
>`Bike Sharing Case Study`


## Table of Contents
- [Project Name](#project-name)
  - [Table of Contents](#table-of-contents)
  - [General Information](#general-information)
  - [Approach Used](#approach-used)
  - [Conclusions](#conclusions)
  - [Technologies Used](#technologies-used)
  - [Acknowledgements](#acknowledgements)
  - [Contact](#contact)



## General Information
- Problem Statement : 
  - A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.
  - A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as possible, and the economy restores to a healthy state.
  
- Business Problem :  
  - You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 
  
- Dataset : 
  - Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

## Approach Used

- Data Understanding and Preprocessing
- Univariate, Bivariate and Multivariate Analysis
- Split Data (Training & Testing) 
- Scaling Data 
- Feature Selection
  - Automatic 
    - Recursive Feature Elimination (RFE)
  - Manual
    - Significance(p_value) and Variance Inflation Factor(VIF)
- Model Selection 
  - Linear Regression
- Residual Analysis
- Model Evaluation 

## Conclusions

- The overall bike rental business seems to have increased from 2018 to 2019, supported by the higher median and larger range of values in 2019.
- bike rental demand is highest during the summer months (July to September) and lowest during the winter months (January, February, November, December).
- Clear weather is the most favorable for bike rentals in all seasons, significantly boosting bike rent counts.
- Snow weather have a negative impact on bike rentals, having the most considerable deterrent effect.
- Summer and fall are the peak seasons for bike rentals, with the highest counts observed during these periods.
- spring shows the lowest bike rent counts, indicating reduced biking activity. 
- The bike demand is almost similar throughout the week.
- Bike rental demand is slightly higher on working days as compared to non-working day.
- temperature shows a positive correlation i.e If temperature rises bike rental demand is higher.
- The model can able to explain 82% of variance of the dataset.
- The residuals are normally distributed.
- The model is able to predict the demand for shared bikes with a high degree of accuracy of greater than 80%.



## Technologies Used
- Pandas: 2.2.2
- Matplotlib: 3.9.2
- Seaborn: 0.13.2
- Scikit-learn: 1.5.2
- Statsmodels: 0.14.4



## Acknowledgements
- This project was inspired by Machine Learning-I Course as a part of IIIT-B PG Program in AI and ML



## Contact
Created by [@engineeramangupta] - feel free to contact me!


