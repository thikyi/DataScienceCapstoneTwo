# Los Angeles County Crime Rate Predication

## Context
Los Angeles has a crime rate of 2,759 per 100,000 people, which is higher than the national average of 2,580 per
100,000 people.I developed a machine learning model that integrates demographics, and
historical crime reports to predict the likelihood of specific crimes occurring in specific
areas within Los Angeles.By providing a data-driven crime prediction model , policy makers and
certain communities can be empowered to implement targeted security measures and
make informed decisions.

## Project Approch

### Data Acquisition
The necessary data was accquired from the sources https://data.lacity.org/Public-Safety/Crime-Data-from-2010-to-2019/63jg-8b9z/explore and https://data.lacity.org/Public-Safety/Crime-Data-from-2020-to-Present/2nrs-mtv8

### Solution Overview

1. [Step1_DataWrangling.ipynb](https://github.com/thikyi/DataScienceCapstoneTwo/blob/main/notebooks/Step1_Data%20Wrangling.ipynb): Combined both data sources above,cleaned the data and handled missing data.
2. [Step2_Exploratory_data_analysis.ipynb](https://github.com/thikyi/DataScienceCapstoneTwo/blob/main/notebooks/Step2_Exploratory_data_analysis.ipynb): Statistically explored the dataset to understand itscharacteristics, patterns, and potential issues, and creating relevant features that capture the characteristics of crime areas.
3. [Step3_Preprocessing_and_training.ipynb](https://github.com/thikyi/DataScienceCapstoneTwo/blob/main/notebooks/Step3_Preprocessing_and_training.ipynb): Prepared data to train the models,did feature engineering for both category and numerical data by using StandardScalar,OneHotEncoding and generated dummies datasets.
4. [Step4_Modeling.ipynb](https://github.com/thikyi/DataScienceCapstoneTwo/blob/main/notebooks/Step4_Modeling.ipynb): Trained the diffrent types of regressions model to predict crime rate trends based on the influenced factors - crime type ,area,victim characteristic,Linear Regression model, Random Forest Regressor, Gradient Boost Regressor, and Decision Tree models are explored,then accessed the model's performance using appropriate metrics such as MAE,MSE and RMSE. Finally, Decision tree has been choosen as the best model, The model file is saved at [models](https://github.com/thikyi/DataScienceCapstoneTwo/tree/main/models).
5. [ProjectReport](https://github.com/thikyi/DataScienceCapstoneTwo/blob/main/reports/ProjectReport_v1.0.pdf) is prepared.

### Footer Note
All files cannot be uploadd into Github because of file limitation. Full data files processed through out the project can be found at 
https://drive.google.com/drive/folders/1Frj4IEXj8Ly_ppH_a_yHnnzUngTYozCs/view?usp=drive_link
https://drive.google.com/file/d/1x7llAVpmfx-RvsLihzpLB-Wt7BSByBW7/view?usp=drive_link



