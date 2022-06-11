# Bike Sharing - Demand is the revenue  :)
> US company Boom Bikes offer service to use bikes for rent /free.Due to covid the company suffered revenue loss as demand for bikes dropped due to lockdown
> As lockdown is not there they want to intelligently play so that they can accelerate revenue. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)



## General Information
- To identify what factors can increase demand for bikes 
- To solve revenue issue in Boom Bikes Company - US
- day.csv is given as dataset overall 16 columns in it




## Conclusions
- The top 3 influence on the bike booking /demand
    -temp : A coefficient value of 4794.5384 indicated that a unit increase in temp variable increases the bike demand by same number
    - yr : A coefficient value of 2075.5328 indicated that a unit increase in yr variable increases the bike demand by same number
    - season_winter : A coefficient value of 1022.4238 indicated that a unit increase in yr variable increases the bike demand by same number
- Summary of train data 
     - Errors are normally distributed is indicated by mean is 0
     - Actual and predicted is almost same - The model is good
     - R2 score of y_train vs y_train_cnt is almost same as model R2 score
- Summary of test data
     - Variance of the residuals (error terms) is constant across predictions. i.e error term does not vary much as the value of the predictor variable changes.
     - Actual and predicted is almost same on test data
     - R2 score of y_test vs y_test_cnt is almost same but has slight variation of .02 which is acceptable when compared with R2 score of model
     - Error terms are randomly distributed and there is no pattern which means the output is explained well by the model and there are no other parameters that can explain the model better.
     ![Pred vs test](https://github.com/vaidehiu/Bikesharing-Vaidehi/blob/main/assets/yestvsyestpred.PNG)

     


## Technologies Used
- NumPy - version 1.20.1
- Pandas - version 1.2.4
- Matplotlib - version 3.3.4
- Seaborn - version 0.11.1
- statsmodels - version 0.12.2
- scikit-learn - version 0.24.1.



## Acknowledgements
This project was created as a assignment required for Executive PG Programme in Machine Learning & AI - IIIT, Bangalore



## Contact
Reach out the creators on,
- Linkedin:
    - [Vaidehi Rao](https://www.linkedin.com/in/vaidehi-u-026a09150/)
- Github:
    - [Vaidehi Rao](https://github.com/vaidehiu)  

