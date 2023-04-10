# ONLINE-PAYMENT-PLATFORM-ANALYSIS-WITH-POWERBI
This Analysis was done for a fintech company I worked for

_Name of company is withheld for certain privacy issues_ 

![](Paymentt.jpg)

## Introduction

The fintech company has an online payment platform where consumer can pay bills, buy recharge,transfer money etc.
Some of the billers on the platform are internet service companies, cable TV, Airlines,
Schools, Utility providers (PHCN, Waterboards, etc), Betting companies, Retail Stores, Hotels and Travel etc. 
Here i did an analysis on the platform usage and below were the questions answered.

## Problem Statement
- Show the Total transaction volume for the six months and monthy
- Show the total users for the six months and monthly
- Show the Total transaction volume by products
- Show the top 5 products requested by customers.
- show the growth rate of transaction volumes per month.
- Show the growth rate of customer on the platform.

## Power BI Concepts applied:
DAX Concepts: Calculated column, Custom Column, Calendar Table created.
Data Modelling: Star Schema

## Data Sourcing
Data was given by the Company in excel format. I downloaded the csv file, and extracted it into Power BI for cleaning, analysis and visualization.
The data contains a sheet/table called Payment Table with 4573 rows and 6 columns

## Data Transformation/Cleaning:
- I cleaned the data efficiently and did some transformations with the Power Query Editor of Power BI.

![](table_payment.JPG)

Some of the applied steps included
- Making first row as headers.
- Created new column for date from the payment date wich came with time and named: [Date]
- Datatype then chnged from 'TEXT' TO 'DATE'.


## Data Modelling
I created a calender table to allow me to slice and dice the data by date attributes such as weekday, month, quarter, and year if needed. 
Power BI automatically created a one-to-many relationship between the [Date] and [Payment] tables resulting in a star schema model. 

![](model_payment.JPG)

## Data Analysis and Visuals
- I added some measures to help in my analysis

#### Measures that were added are shown below; 
- [Month on Month Growth rate of users] 

![](mom_users.JPG)

- [Month on Month Transaction Growth Rate]

![](mom_payment.JPG)

Below is the Dashboard I created 

![](payment_dashboard.JPG)

[LINK TO POWERBI DASHBOARD](https://app.powerbi.com/view?r=eyJrIjoiYTIzNjY2YjMtZDg1NS00YzdhLWJmYzctNThiYTk2MzBkMTZkIiwidCI6IjY4ZDBlMjhiLTg3NTUtNDgzMi1iM2JjLWRhOGQwNjM3YzY5ZCJ9&pageName=ReportSection)

### From the dashboard, it is observed that;
#### Total transaction volume made in the six months from April to September = $106M,and April has the highest with $21M


![](PaymentVol.JPG)

#### Total number of transactions made in the six months from April to September = 4,573
#### Total number of Users = 3,295
 
![](Payment_User.JPG)

#### Show the Total transaction volume by products

![](Payment_txVol.JPG)

#### Show the top 5 products requested by customers.

![](payment_top.JPG)

#### show the growth rate of transaction volumes per month.

![](payment_tx_growth.JPG)

#### Show the growth rate of customer on the platform
![](Payment_growth.JPG)



## Conclusions & Recommendations
-Show the top 5 products whose availability is critical to ensure sustained revenue










