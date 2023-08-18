# Atliq Stores Supply Chain Analysis

![](IntroductionPix.jpg)

## Introduction
This Power BI project focuses on analyzing the supply chain of a fictional grocery store, **Atliq Stores**, which distributes products to three different states. This project focuses on analyzing a dataset of customer orders and products in order to improve supply chain efficiency and reduce costs, by better understanding their customers, products and delivery time. and help the company make data driven decisions.

**_Disclaimer_**: All datasets and reports do not represent any company, institution or country, but just a dummy dataset to demonstrate my capabilities on power BI.

## Problem Statement
Atliq Stores is currently facing operational challenges that are hindering its supply chain efficiency and customer experience. To overcome these issues, the project focuses on harnessing the power of data analysis. By thoroughly examining customer orders and product information datasets, my aim is to uncover underlying factors impacting customer behavior, product preferences, and delivery timelines. My primary goal is to identify critical patterns, obstacles, and inefficiencies within the supply chain process. Through data-driven insights, i intend to implement strategic solutions that streamline operations, enhance cost-effectiveness, and ultimately elevate customer satisfaction

## Skills demonstrated
The following power BI features were incoporated
- DAX
- Quick measures
- Data modelling
- Filters
- Power query

## Data Modelling:
Automatically derived relationships are adjusted to remove and replace unwanted relationships with the required.

Adjusted Model     |     Auto Model
:------------:|:-----------:
![](ActualDataModel.png) | ![](DerivedDataModel.png)

The data model is a snowflake schema
There are 4-dimension tables and 2 fact tables. The dimensions table are joined to the fact table with a one to many and one to one relationships

## Visualization
The report comprises of 4 Pages
1. An Overview 
2. Customer Analysis 
3. Product Analysis
4. Delevery Analysis

You can interact with the report [here](https://app.powerbi.com/view?r=eyJrIjoiMTczYzBiOGYtZjc4NC00NGM0LWE5NjUtNjllMjUzOWJlNzY2IiwidCI6IjM3ZGNlYjFkLTdhYzMtNDA2Ny04NjJiLTU5NGQ5ZjM2MzUyMiJ9)

# Analysis
--------------

### No of Goods Ordered each month
![](NoOfGoodsOrderedByMonth.png)

### Efficiency Assesment
![](Target.png)
It appears that improving infull performance should be a priority, given that it has the lowest achieved percentage



