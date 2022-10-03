# Exploratory Data Analysis

**By**: Ensun, Stephen and Abhradeep

This repository contains our group presentation for our MSDS 610: Communication for Analytics course, where we are presenting our views on EDA and it's importance.

## Introduction 
![29xp-meme-mobileMasterAt3x-v3 (1)](https://user-images.githubusercontent.com/109040294/193493736-fed7dd59-c80a-4105-882e-1e711e3d8396.jpeg)

## Goal 
For this presentation we wanted to highlight the importance of EDA and showcase some basic EDA steps that we can implement to have a better understanding of our data. 

## The Data
The dataset we chose to work with is the [Cars dataset](https://github.com/Abhradeep1994/msds610-EDApresentation/blob/main/cars.csv). This dataset contains  a total of 392 rows and four variables which are:
- MPG
- Cylinder
- Engine 
- Weight

## Our Process

### Data Processing 
- Collecting basic information regarding the data:
<img width="574" alt="Screen Shot 2022-10-03 at 1 12 41 AM" src="https://user-images.githubusercontent.com/109040294/193530574-4ade3ac8-cf25-4b10-9418-1f43b85e4200.png">
    - Data types
    - Missing Values
    - Treatment of missing values(There can be other ways, we are replacing the missing values with the median value of that variable)

### Plots

#### Histogram:
Histograms are plotted to check the distributions of the variables in our dataset.
<img width="904" alt="Screen Shot 2022-10-03 at 1 16 01 AM" src="https://user-images.githubusercontent.com/109040294/193531140-984c6d9b-fb58-4938-b3ac-20710bc8ebb4.png">


#### Scatter Plots    
Scatter plots helps in understanding relationship between two variables which can help us with feature engineering, reporting and modelling. Sometimes it also helps us in identifying aspects of the use case which me may not have considered.

<img width="902" alt="Screen Shot 2022-10-03 at 1 19 23 AM" src="https://user-images.githubusercontent.com/109040294/193531688-4cf97767-e602-42d1-9b12-7b3c773e3ac6.png">

#### Box Plots
Box plots helps us in identifying outliers and range of data for a variable
<img width="501" alt="Screen Shot 2022-10-03 at 1 19 51 AM" src="https://user-images.githubusercontent.com/109040294/193531794-34841137-1372-4717-8e18-82ea47259db4.png">

### Conclusion
We have focussed on few aspects related to EDA. We can create other kinds of plots and do a lot more analysis in our EDA. One important aspect that needs to be taken into consideration is you need to have some domain knowledge to make best decisions regarding your data and next steps.

Thank you for taking the time to read about our presentation on EDA. We hope you realized the importance of EDA and why a data scientist should do good EDA before taking any decision or steps

### Technical Specifications

To use this notebook you need to run the following command:
```
git clone https://github.com/Abhradeep1994/msds610-EDApresentation.git
```
You also need the following python libraries:
```
pandas src ='https://pandas.pydata.org/'
matplotlib src ='https://matplotlib.org/'
```
