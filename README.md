# Conditional Release Grant Rate
CIND820 – Big Data Analytics Project

Introduction

The Parole Board of Canada (PBC) is part of the criminal justice system in Canada. The PBC is an independent governmental agency that has “exclusive authority, under the Corrections and Conditional Release Act (CCRA), to grant, deny, and revoke parole for offenders serving sentences of two years or more” (Parole Board of Canada, 2021). 

As part of the Government of Canada’s open data initiative, the PBC publishes annually on the number of conditional releases by its final approved release decisions Parole Board of Canada, 2018). The following study is based on the “Conditional Release Grant Rate” data provided by the Parole Board of Canada (PBC).

Revised Research Questions

The study is centred on the application of classification algorithms in relation to parole decision making. Classification methods are suitable for the dataset as the dependent variable in this case is a binary variable (Grant Rate Qualifier) with two classes. As offenders continue to move through the criminal justice system, there is value in understanding and predicting if an offender’s conditional release can be predicted given a set of variables. Since the inception of this study, the research questions have gone through several revisions as the project moved through the scoping and literature review stages. The research questions below are the latest versions prior to the final revisions:
1.	Based on Singh, Jain, and Kumar (2017)’s study, how do classifier algorithms such as Decision Trees, neural networks and Random Forest compare when used to predict the grant rate qualifier? How do the results compare to those obtained in the Singh, Jain, and Kumar study?
2.	How do each of three classifiers compare against one another in terms of efficiency, performance, and accuracy?

While it was the intention of the project to replicate the Singh, Jain, and Kumar (2017)’s study. The research questions had to be revised due to several limitations. In particular, research question 1 had to be adjusted. A model using the neural network classifier was unfortunately not feasible due to time constraints. As such, the adjusted research question is as follows:
1.	How do classifier algorithms such as Decision Trees, Logistic Regression and Random Forest compare when used to predict the grant rate qualifier? How do the results compare to those obtained in the Singh, Jain, and Kumar study?
Logistic Regression was selected since this was a classifier previously studied in prior courses and presented a good opportunity to further my knowledge of it. 
The second research question remained unchanged. Using the revised selection of classifiers, the models will still be tested for efficiency, accuracy and performance as demonstrated below.

Methodology
1.	Data Acquisition
2.	Exploratory Data Analysis
3.	Dimensionality Reduction, Balancing the Dataset & Feature Selection
3.1	Dimensionality Reduction
3.2	Balancing the Dataset
3.3	Feature Selection
4.	Classification Algorithms
4.1	Data Load
4.2	Training and Testing Splits
4.3	Cross Validation
4.4	Final Variable Preparation
4.5	Modelling

Files in this directory
a) Exploratory Data Analysis - Methodology step 1 and 2
b) Dimensionality Reduction & Feature Selection - Methodology step 3
c) Final Models - Methodology step 4
