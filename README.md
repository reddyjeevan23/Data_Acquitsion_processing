# Building dataset on mobile specifications using web scraping 
## Documents to look for:
1) ProjectDSCII.ipynb - This is the Jupyter file which has the entire code to run. It is subdivided into two sub cells.
       a) Main cell having the web scraping code and 
       b) Having the code for writing into CSV. You need to open the file using Jupyter and run the cells one after the other.
2) Creating Dataset Using Web Scraping.pptx - This Powerpoint presentation has generic overview of the project.
3) Dataset.csv - This is the output dataset of the project.

## Objective:

The objective of this project is to build a dataset that has all the specifications and features of Mobile Phones. We have considered the below website for the development of the project. Website information: https://www.gsmarena.com 
Web scraping is the technique/method used for data extraction from this processing by parsing through required the tags

## Methodology:

We have used web scrapping methodology to scrap the data from https://www.gsmarena.com/

## Terms of Use:

As per the legal terms of the website, information can be scraped for " the  Documents may be used solely for personal, informational, non-commercial purposes”.

## Desired Dataset:

The dataset contains below few columns that are shortlisted to be part of the dataset for our analysis.

●	BRAND	
●	MODEL	
●	OS	
●	PRIMARY CAMERA	
●	SELFIE CAMERA	
●	GPU	
●	CPU	
●	INTERNAL MEMORY	
●	SENSORS	
●	BATTERY
●	PRICE

## Process Flow:

Our project flow is carried out in various steps. Below are the steps involved to achieve our goal.

Step 1: Getting html output from the URL using Beautiful Soup.

Step 2: Looping through all the brands and building URL.

Step 3: Looping through all the Mobile model and building URL for next step.

Step 4: Parsing through the table data and getting the required features.

Step 5: Writing all the data into CSV.

## This data set can be used for:

a)	Comparison Engine – Comparing different mobile models and their features based on the specifications and other parameters.
b)	Business Analysis – It can be used has the source to understand the latest trends in mobile technology, boom factors of mobiles and to analyze the business growth of various mobile brands.
c)	Individual Analysis - An individual can utilize this data set as for his personal thesis works

## Challenges/Limitations: 

Only brands which were available in the website was considered for this project but there are lot more brands whose data is absent in this dataset. 
In the website, not all the specifications of the mobile are officially verified or guaranteed. So, there are chances of incorrect data in the set. 
The major challenge in this project was the rate limit of the website which was not allowing us to hit the server many times and in return had a restricted output for a single run.



