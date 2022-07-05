

# Students Adaptability Level in Online Education

![dataset-cover](https://user-images.githubusercontent.com/98824143/177305309-0a8a9501-48a2-4cff-9c2e-acb5c6c23d5c.jpg)

## Introduction
Distance learning (DL) is an educational process using technologies that provide communication between students and teachers at a distance, without direct contact.

Distance learning is the interaction of a teacher and students with each other at a distance, reflecting all the components inherent in the educational process (goals, content, methods, organizational forms, teaching aids) and implemented by specific means of Internet technologies or other means that provide for interactivity.

Distance learning is an independent form of learning, information technology in distance learning is the leading tool.

## Context
Since as a beginner in machine learning it would be a great opportunity to try some techniques to predict the outcome of Students’ Adaptability Level Prediction in Online Education using Machine Learning Approaches

## Inspiration
To get an idea about the effectiveness of online education

## Dataset
  https://www.kaggle.com/datasets/mdmahmudulhasansuzan/students-adaptability-level-in-online-education
  
### Here we Analyse Students Adaptability Level in Online Education In Different aspect.


## Dataset Content
The target feature is
* Adaptivity level

The feature sets are:
* Gender
* Age
* Education Level
* Institution Type
* IT Student
* Location in Town
* Load-shedding
* Financial Condition
* Internet Type
* Network Type
* Class Duration
* Self LMS
* Device

## Structure of Project

### Task 1: Load the Data and Import Libraries

      * Load the dataset using pandas.
      * Import essential modules and helper functions
      * Explore the dataframe using the head().
      
### Task 2: Inspect the Data

       * Explore the dataframe using the shape, info() functions.
       * Check the null values
       * Get Statistical Overview using describe()
       
### Task 3: Visualizing and Analysing the data

  Analyse the Datset based on the visualizations. Here I use using Seaborn & Matplotlib to visualize the data Pandas functions used to analyse data

### Task 4: Conclusion

 From the Analysis made some conclusion.
 * Gender - Men are easier to adapt to new knowledge, the level of poor adaptation between men and women is approximately the same.


* Age Range- The stark differences in adaptivity by age range is very interesting. Respondents between Ages 1–5 did not achieve   high adaptivity at all.High adaptivity is recorded mostly among 11–15 year olds and 21–25 olds typically in Junior HighSchool   and Tertiary Institutions 


* Financial Condition - It should also be noted that the best adaptivity of the material is observed in the middle class.


* Location- this variable tests whether students resided in the town or rural areas. The results showed that students in the     urban area adapted better than those in rural areas. We can infer access to facilities, basic amenities,better internet         connectiviy as reasons for this.


* Load shedding - This tests the level of load shedding of electricity which in this case is inversely proportional to           availabilty of power supply.Students with poor supply tended to adapt at less levels than their counterparts with load shedding and consequently better electricity power supply.


* Internet Type - Students who used WiFi had higher frequencies of high level adaptivity than those who used mobile networks,  as most WIFi networks make use of high speed internet connectivity,we can infer that the better internet connectivity led to better ability to concentrate during classes.


* Self LMS- this variable refers to availability of the educational institutions Learning Management System (LMS). Although a smaller portion of the sample size were exposed to LMS, they had higher rates of high adaptivity to online education.Interestingly, the level of Low adaptivity is also relatively minute compared to those who werent using the LMS.

### Task 5:  Machine Learning Models Building
  Applied some models 
 - Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- KNeighbors Classifier
- XGBoost Classifier

## Comparison of all Models

| Model | Accuracy Percentage | Time taken |
| --- | --- | --- |
| Logistic Regression | 70.86 % | 0.229 |
| DecisionTree Classifier | 90.39 % | 0.023 |
| RandomForest Classifier | 91.05 % | 0.687 |
| KNeighbors Classifier | 79.47 % | 0.085 |
| XGB Classifier | 91.39 % | 0.848 |

## Conclusion
* Time taken is maximum for XGB Classifier and minimum for DecisionTree Classifier.

* XGB Classifier is the best model from among the models trained to predict the accurate result with an accuracy of 91.39 % and time taken to execute is 0.848.
