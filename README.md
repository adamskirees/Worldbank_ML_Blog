# Installation Notes
There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python. Only basic python libraries have been used, all are listed below: -

    * Pandas
    * Numpy
    * MatplotLib
    * sikit learn marchine learning lib

# Project Aims and Motivation
This project will convert raw data from the worldbank.org website and shape to build a decision tree classifier that predicts if a countries GDP will be growing. The specific questions covered are:- 

1) Can we create features from the time series data, capturing the information into a single column variable. Is this enough for accurate classification? 
2) What are the key variables that predict if a country will have GDP growth. 
3) Can we measure performance for this and which metrics best measure the model performance ? 

It should be noted that the GDP figures were also taken from the worldbank website, which we developed a rule for the classification. The rule was the country needed to show GDP growth of 1.5% over at least 3 years to be classified as growing (1) or not (0). So the classification was a binary varaible and yes, we could have identified this easily from the given data. However, the purpose of the exercise was to create features, create a rule for the classification of GDP and then create a model around that. 


# Files 
Main file used was the data.ipynb which was coded in VS code. 

# Results

Findings for this project are best viewed at this medium blog post -> https://medium.com/@adamtrees/classification-model-for-determining-countries-gdp-3ec63e1b613c 

# Licencing / Other Info
This data was taken from the worldbank.org website from various searches based around economic and societal indicators. Data is free to use from the website www.worldbank.org
