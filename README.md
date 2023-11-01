
![download](https://github.com/Datafyde/Guided-Project-Data-Heroes/assets/135570337/aff0b01a-e03e-482f-a9f6-2ff267ad2d2e)

# Guided-Project-Data-Heroes
This is the official repo for the Data Heroes Guided Project

# Dataset

![Screenshot 2023-10-14 173736](https://github.com/Datafyde/Guided-Project-Data-Heroes/assets/135570337/96693b40-07f5-43fe-9372-c5ffd95925dc)

The data was sourced from Kaggle and is about a hotel booking

## Data Inspection
Dataset shape: 21,996 rows and 32 columns 						
Missing values:	agent column has 3099	missiing values. The values were kept.		
	              company column had 20,691	missing values. The column was dropped to prevent skewness in the data				
Duplicates: Duplicates were ofund in the data and were addressed in Power Query	
Outliers were discovered but were kept.		
The data was found to be inconsistent but the data types were consistent

## Data Cleaning
Merged the 2018, 2019, 2020 datasets
Duplicates were removed 
NULL values were replaced with empty string
Categorical data displayed as 1s and 0s were replaced with the appropriate text
Created arrival date column
Extracted specific date values from the reservation status date

## Data Modeling
Created the different dimension tables:

#### Hotel DImension Table
duplicated final hotel data
undid all previous transformation
removed all columns except **hotel**
created hotel ID column

#### Location DImension Table
data was extracted from [statistic times](https://statisticstimes.com/geography/countries-by-continents.php).
we cleaned the data, only  extracting the coliumns needed

#### Date DImension Table
					

