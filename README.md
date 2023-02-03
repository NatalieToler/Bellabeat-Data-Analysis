# Bellabeat: How Can a Wellness Technology Company Play it Smart?

Tableau Dashboard
Tableau Presentation to Skateholders

## Introduction

In this case study I will be using the six steps of the data analysis process to complete a senerio. 

Ask
Prepare
Process
Analyze
Act

## Background

Bellabeat is a high-tech manufacturere of health-focused products for women. They are a successful small company looking to expand into the global market of smart devices. The cofounder and CEO, Urška Sršen wants the analyst team to analyze smart device fitness data to gain insight into how custombers use non-Bellabeat smart devices so that she and the marketing team can use those insights to unlock new growth opportunities. 

Deliverables:
1. *A clear summary of the business task*
2. *A description of all data sources used*
3. *Documentation of any cleaning or manipulation of data*
4. *A summary of analysis*
5. *Supporting visualizations and key finding*
6. *Top high-level content recommendatiaons based on the analysis*

## 1.  Ask

#### **Business Task: Analyze FitBit Fitness Tracker Data to gain insights into how customers utilitze fitness trackers and discover trends and insights for the Bellabeat marketing team.**

Primary Stakeholders: Urška Sršen and Sando Mur, Bellabeat's executive team

Secondary Stakeholders: Bellabeat's marketing team

## 2.  Prepare

Data Source: A public domain dataset available on Kaggle of FitBit Tracker Data
  - The Data is stored in 18 csv files
  - Generated by 30 FitBit users who consented to the use of their personal data
  - The data tracks user's activity bewteen 12 March 2016 to 12 May 2016
  - Data collected inluded physical activity recorded in minutes, heart rate, count of steps per day, daily activity, and sleep monitoring.
  
  Does this data set hold up to ROCCC?
    - Reliable: Yes/No. Besides the weight input all of the data in this set is set by the device and not the users which makes the data more reliable on a individual data point level. However the data set is also very small with only 30 individual participants which is not going to give us a reliable insight into trends of the majority of fitness tracker users. 
    - Original: Yes. The dataset is original, using data directly from FitBit users. 
    - Comprehensive: Yes. While the small sample size is still a concern here, the amount of different activity tracked is a comprehensive set of the features of fitness trackers, including the features that Bellabeat is interested in. 
    - Current. No. 

The dataset provided is a public domain dataset on Kaggle. The data contains personal fitness data from thirty fitbit users. The users consented to the use of their fitbit data, including heart rate, sleep monitoring, and physical activity. This dataset is a good start at getting an idea of the habits of personal fitness tracking device users. However there are limitations to this data and having further datasets would provide a better image at the wholistic usage of fitness trackers. 

<sub>*Limitation and Bias concerns: The data set is small considering how large the personal tracking device industry is and therefore we will be limited in the scope of our conclusions. This data is also skewed towards a population who already uses tracking devices consistently. While finding ways to draw those existing costumers to Bellabeat's devices will be valuable, it would also be beneficial to have data on fitness users who are less consistent with their tracker usage to find ways to extend the longevity of general use, as well as fitness habits of potential customers which could help sell fitness trackers to people who don't already have one. Additionally, Bellabeat's business model is focused on women's health. This data does not include gender identity. To be in allignment with Bellabeat's business model, having data this is specific to womens fitness and wellness habits would allow for an even more tailored analysis.*</sub>

Since the data is in Kaggle I will be using a kaggle notebook to analyse the data. 

