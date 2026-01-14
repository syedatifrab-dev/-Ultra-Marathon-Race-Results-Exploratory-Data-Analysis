# -Ultra-Marathon-Race-Results-Exploratory-Data-Analysis
This project performs an in-depth Exploratory Data Analysis (EDA) on a dataset containing over 7 million ultra-marathon race records. The analysis focuses on cleaning the data, filtering for specific race types (50km and 50 miles) in the USA for the year 2020, and visualizing performance trends across different demographics.


**Project Objective**

The primary objective of this project is to perform a comprehensive Exploratory Data Analysis (EDA) on a massive dataset of ultra-marathon race results spanning two centuries. The analysis specifically focuses on narrowing down over 7 million global records to a targeted subset: 50km and 50-mile races held in the USA during the year 2020.

**📊 Dataset Overview**
The analysis utilizes "The Big Dataset of Ultra Marathon Running" sourced from Kaggle.

Original Size: 7,461,195 records.

Time Span: Two centuries of race results.

Key Features: Event name, distance, number of finishers, athlete performance, gender, age, and average speed.

**🛠️ Technologies Used**
Language: Python

Libraries: * Pandas: For data ingestion, filtering, and cleaning.

Seaborn & Matplotlib: For statistical data visualization.

**🧹 Data Cleaning & Preparation**
Before analysis, the data underwent a rigorous cleaning process:

Filtering: Limited the scope to USA races in 2020 for 50km and 50mi distances.

Feature Engineering: Calculated the athlete_age by subtracting birth years from the event year.

Schema Standardization: Renamed original columns to more readable formats (e.g., Event dates to race_day, Athlete average speed to athlete_average_speed).

Handling Missing Values: Identified and removed records with null values in critical performance columns.

Type Conversion: Standardized data types for age (integer) and average speed (float).

**📈 Key Insights & Analysis**
1. Speed Distribution by Distance and Gender
The project analyzed the average speeds across the two primary race lengths:

50km Races: * Male: ~7.74 mph average speed.

Female: ~7.08 mph average speed.

50mi Races: * Male: ~7.26 mph average speed.

Female: ~6.83 mph average speed.

2. Performance by Age Group (50-Mile Races)
We examined which age groups exhibited the highest and lowest average speeds (minimum 20 race entries):

Top Performing Ages: Athletes aged 29 (7.90 mph) and 23 (7.78 mph) were the fastest on average.

Lowest Performing Ages: Runners in their early 60s (ages 60, 61, 62) showed the lowest average speeds, ranging from 6.26 to 6.36 mph.

**🖼️ Visualizations Included**
The notebook includes several critical plots to visualize the data distribution:

Histograms: Showing the participant count by race length and gender.

Distribution Plots: Visualizing the density of athlete speeds for 50-mile races.

Violin Plots: Comparing speed distributions between genders across both 50km and 50mi categories.






Top Performing Age: 29-year-olds averaged the highest speed (~7.90 mph).

Master Athletes: Significant participation was noted in the 50-60+ age groups, albeit with a natural decline in average speed.
