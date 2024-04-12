# Customer Identification for Bank Marketing Campaign

## Introduction
An app is developed for bank marketing campaigns; that target customers interested in making term deposits. App is based on 16 inputs that predict whether a customer will deposit or not? The app was trained using <b>sklearn</b> models and is developed in <b>Streamlit</b>. 

## Dataset
The dataset consists of actual information obtained from a marketing campaign of a Portuguese banking institution. The bank launched this campaign to increase the term deposits. Often; each customer was contacted more than once, to determine as a depositor or non-depositor.

The dataset was acquired from UCI (University of California, Irvine) repository. It is avalailable in link: https://archive.ics.uci.edu/ml/datasets/bank+marketing). The dataset consists of <b>11162</b> rows and <b>15</b> features.    

## Problem Statement
Marketing a product or a service is very challenging. Identifying the right customer is vital for the marketing team. This can significantly reduce the resources and time. Furthermore, this allows the team to position the product correctly. Unfortunately, finding the right customer can be exhaustive and complicated. There are many features to consider and huge data to analyze. Thus conventionally; the marketing team relies on experience of the marketing experts and feedback of team. 

Due to vast facts originating from so many features; a mistake in identification of customer is inevitable. Missing a customer segment results as a loss to the institution. On contrary, identifying wrong segment of customers will result in wastage of resources and time (As faults in strategy is confirmed at a later stage). 

Therefore, such a project is vital for product marketing. 

## Goal
This work was performed as a personal project. The motivation was to obtain analysis of bank marketing campaign and identify customers that will make term deposits. For highest possible term deposits, a high accuracy was desirable for customer classification.   

An app classifying depositing customers, provides a very straightforward and intuitive means for identifying customers. This saves substantial <b>resources</b> and <b>time</b>. Also, this apporach is easily reproducible, thus; provides a <b>common</b> marketing platform to all the marketing teams and bank branches. The app will be utilized by the marketing team for accurate customer selection. Reduced errors in identifying customers will <b>increase</b> the bank deposits. 


## Installing Dependencies
Foremost running the project, installing the dependencies is essential. 
* Ensure Python 3.8.8 or later is installed in the system. 
* All required libraries are listed in "requirements.txt". These are easily installed; by running the following command in project directory
```bash
pip install -r requirements.txt
```

## Run Project
Application file "app.py" runs using command 
```
streamlit run app/app.py
```
**Note:** To run any project script, directory location must be correct.
   
