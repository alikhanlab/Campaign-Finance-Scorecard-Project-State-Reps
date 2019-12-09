# Campaign-Finance-Scorecard-Project-State-Reps
The final project for CAS CS 506 Computational Tools for Data Scince


Project Title: Campaign Finance Scorecard - State Reps
Team Members: Alikhan Nulanuly, Xing Yiquan,Michael Harding

## Background
In 2016, in an effort to increase transparency of political campaign finance Solomon Khan built the Explore Campaign Finance website to help citizens and journalists understand how much money was in politics and explore its influence. Unfortunately the data on the website had not been updated since 2016 and it focused on federal elections and not state elections, which is our area of  interest. Hence in this project we want to develop a campaign finance scorecard for Massachusetts State Reps to give an objective presentation of campaign finance in the state.

## Problem Statement
To develop a Campaign Finance Scorecard for elected Massachusetts State Representatives based on publicly available campaign contribution data. The Scorecard will be an objective presentation of donors’ contributions for each State Rep to answer the political research questions.

## Methodology

- Data Collection and Cleaing
![Alt text](https://github.com/alikhanlab/Campaign-Finance-Scorecard-Project-State-Reps/blob/master/pics/data_preporation.png)

- Clustering state reps candidates

We perform k-means clustering and used number of unique donors over quarters(2 election cycles) as a feature set per candidate. There are 3 clusters, because we assume candidate fundraising ability and popularity can be binned into three categories(high, medium, low).
The candidates in the same cluster means they are similar to each other and different than candidates from other clusters. 

- Visualise finding 

Visualisation includes research question answers to:
Q1) Number of unique donors for all the quarters for the past 2 election cycles from 2015-2018
Q2) Distribution of contributions across 5 contribution bands (<$25, $25-$99, $100-$249, $250-$499, $500-$1000)
Q3) Geographical distribution of donors (using zipcodes)
Q4) Monthly donations by PACs (Political Action Committees)
Q5) PAC donations by industry sector
Q6) Donations by Employer Types (excluding PACs)
Q7) Donation by Donor Type


Detailed final analysis report HERE
