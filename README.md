#  Exploring-crime-trends
Checking out the safety level in the United States of America from the year 2020 till 2023

---
# Introduction
This data set is called the crime data which was sourced from Kaggle. The crime data will be used to carry out an analysis of the level of security in the United States of America from 2020 till the present. The analysis will benefit law enforcement agencies, criminal justice professionals, policymakers, and the public, to knowing areas where crime prevention policies should be implemented more, how movements should be done and at what time, and where to deploy more resources used in crime prevention such as security and checkpoints.
The crime data set contains 28 columns in its raw form and 815,883 rows.

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

---
# Data Wrangling

The crime data set had a significant number of impurities which did not make it fit for analysis
For instance, there were missing values, irrelevant data/columns, and invalid entries in the crime data set
Here  are some steps taken to ensure data was transformed and fit for analysis
Discovery: the crime data set was studied to become acquainted to identify the issues to be addressed such as nonstandard values, null and missing values, etc.
Structuring: the data in its raw format is unusable. Hence, thorough data cleaning using the power query of Microsoft PowerBI was carried out. Cleaning such as changing column names, removing and replacing null values, filtering, splitting columns to keep the necessary data, and checking for duplicates.
Data transformation was done to get the crime data set ready for analysis. This was in the form of using existing data as “date occurred” and “date reported” to calculate the response rate. This enriches the data set.
Once the above were carried out, the data was ready for visualization and reporting.

---
# ANALYSIS

**SUMMARY  STATISTICS**
- Overall, **total crimes** amounted to 112.95K crimes from the year 2020 till the year 2023
- The **number of genders** in the United States of America is 3 in number (Male, Female, and Others)
- Races also amounted to 3 (White, Hispanic, and Others)
- It seems the most **common weapon** used is the fist as the majority of the crimes are usually battery or assault.

**Crimes and crime scene by area**
From the analysis, 77th Street had more crimes than any other area amounting to 8,700 crimes. This is also located in North America
The least crimes are in the Olympics area with a total of 6,400 crimes
That is a difference  of 2,300 crimes. South America does not match the concentration of crime scenes found in North America. 
Although some of the crime scenes extended to Europe, North America took the trophy as demonstrated in another analysis.

**Crimes by age group**
Adults had more attacks than any other age group with a total of 10,200 crimes.
The least crimes are child-related crimes with a total of 1900 crimes
That is a difference  of 8,300 crimes between adults and child-related crimes.

**Crime by status**
About 61,000 crimes are still under investigation
This is high compared to the Juvenile categories.
This could be due to lack of information and evidence which could help in solving the case

**Crime by race**
The Hispanic race is more likely to become victims in the United States
With 50.85% of crimes suffered by the race
The Whites are in fact the least with 16.78% of the crimes suffered by them
The reason why the Hispanics are the most is because they do not have enough security in their vicinity. Another issue is the response rate (in days) is on the increase due to corruption in the system.

**Response time**
The table shows a record of the response time in days from the 1st of January 2020 which started with zero.
Response time began to increase up to more than a year presently.
For instance, on the 22nd  of January 2020, the response rate rose to 21 days which is equivalent to 3 weeks
Females are more likely to become victims in the United States
With 59.79% in the number of crimes suffered by the female gender females are more on the victim scheme than mill and others 
Others are the least with 1.43% of the crimes suffered by them
The reason why the females are the most is because they do not have enough strength to defend themselves from their predator

**Crimes committed monthly from 2020 to 2023**
July has the highest number of crimes, followed by August
This could be the result of idle time during the summer holidays
July’s crime hits up to 10,900 and 10,800 in August.
The least is December with a total crime rate of 6,900 crimes because of the weather which goes as cold as ice in most areas especially, at the end of the month.

**Crimes by time of occurrence**
The line graph below shows that crime occurs mostly when it is almost midday starting from 10:00 am.
A total of 2,700,000 and 1,400,000 crimes occur between 10:00 am and noon.
Additionally, no crime was spotted as of 05:00 am. This might be because the majority of the crime committers are asleep as of then. 

---
# Recommendation

More crime prevention personnel should be assigned to those areas for patrol in North America to ensure that the response rate of crime will be reduced.
The investigation should be carried out till the case is closed either by catching criminals responsible for discontinued when the trial stops
Awareness should be made so that citizens will reduce movements when the rate of crime is on the high, especially women.

---
# Summary and Conclusion

**It is seen that:**

77th Street suffers the greatest number of crimes which is in North America with a cumulative of 8,700 crimes committed.
Adults population are the most in population by age range who suffer attacks from criminals with a total of 10.2k criminal attacks suffered by them.
Women are the most abused by criminals especially by their partners be it by physical assault, rape, and vandalism with a 59.79%
North America has the highest crime rate as of 2020 till date
Response rate has increased from 0 days to more than a year even while some cases are still under investigation.

---
# Visualization to be provided upon request


















