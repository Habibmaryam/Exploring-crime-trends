![image](https://github.com/Habibmaryam/exploring-crime-trends/assets/117365835/763dbeb3-608e-462e-820f-b895fd42e914)![image](https://github.com/Habibmaryam/exploring-crime-trends/assets/117365835/cff3b3af-3be2-4319-9b2c-1f977eb5b197)# Exploring-crime-trends
Checking out the safety level in the United States of America from the year 2020 till 2023

---
# Introduction
This data set is called the crime data which was sourced from Kaggle. The crime data will be used to carry out an analysis of the level of security in the United States of America from 2020 till the present. The analysis will benefit law enforcement agencies, criminal justice professionals, policymakers, and the public, to knowing areas where crime prevention policies should be implemented more, how movements should be done and at what time, and where to deploy more resources used in crime prevention such as security and checkpoints.
The crime data set contains 28 columns in its raw form and 815,883 rows.
![image](https://github.com/Habibmaryam/exploring-crime-trends/assets/117365835/a8a19c5a-a60b-4b95-a790-bcc291631ada)

---
# Data Questions 
1. Which of the areas had the highest crime rate since the year 2020?

2. What is the response rate like from when the crime is being committed?

3. Which gender is more vulnerable to victims of crime from 2020 to 2023?

4. Which of the areas had the lowest crime rate since the year 2020?

5. Which month had the highest crime rate over the years?

6. Which race is more prone to becoming victims of criminal occurrence?

---
# Data Cleaning

Here are the activities carried out using the power query editor of Microsoft PowerBI to ensure that the crime data set is fit to carry out analysis:

1. **Removing null and missing values**

The data set contained a lot of null values. 
The “Victim gender” column had null values which were replaced with “Others” because each record should be Female, Male, or Others.
The “Cross Street” column also contained a lot of null values and hence, removed to not have too many discrepancies in my analysis.
Missing values were also filled out accordingly

2. **Checking for duplicates**

There were no duplicates detected in the crime data set

3. **Renaming columns**

Most of the columns were renamed for ease of identification during the visualization stage.
For instance, victim age, victim race, and victim gender columns were renamed for ease of identification during visualization.

4. **Irrelevant columns**

Irrelevant columns were removed as they would not be needed during the data visualization and analysis process.
For instance, the “Area code”, “Crime code”, and “Monocodes” were removed.

5. **Split columns**

Columns were split by a delimiter to extract the relevant data for visualization.
For instance, the weapon column was split to extract just the primary name of the crimes committed. 

6. **Changed data types**
   
Data types were changed to suit the data entries in the column
For instance, the longitude and latitude columns were changed to suit the location data type.






