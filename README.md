# Bank Term Deposit Prediction: Marketing Campaign Analysis

## Project Overview
This project analyzes data from a Portuguese bank’s telemarketing campaigns to predict which customers are most likely to subscribe to a term deposit. The goal is to improve targeting efficiency and marketing ROI using a classification model.

## Dataset Description
The dataset contains 45,211 records collected from direct marketing campaigns conducted by phone between May 2008 and November 2010. It includes 16 features and 1 target variable.

### Feature Categories

**Personal Information**
- age: Customer's age  
- job: Job type  
- marital: Marital status  
- education: Education level  
- default: Credit default history  
- balance: Average yearly account balance  
- housing: Has a housing loan  
- loan: Has a personal loan  

**Current Campaign**
- contact: Contact communication type  
- day: Last contact day  
- month: Last contact month  
- duration: Last call duration (seconds)  
- campaign: Number of contacts during the campaign  

**Previous Campaign**
- pdays: Days since last contact (-1 if never)  
- previous: Number of prior contacts  
- poutcome: Outcome of previous campaign  

**Target Variable**
- y: Whether the client subscribed to a term deposit (yes/no)

## Business Challenge
The objective is to:
- Identify key factors influencing subscription
- Prioritize high-potential clients
- Reduce unsuccessful contact attempts
- Optimize marketing strategies

## Technologies Used
- Python  
- Jupyter Notebook  
- pandas, scikit-learn, matplotlib, seaborn  

