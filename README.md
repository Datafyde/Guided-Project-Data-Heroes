
![download](https://github.com/Datafyde/Guided-Project-Data-Heroes/assets/135570337/aff0b01a-e03e-482f-a9f6-2ff267ad2d2e)

# Guided-Project-Data-Heroes
This is the official repo for the Data Heroes Guided Project

# Dataset

![Screenshot 2023-10-14 173736](https://github.com/Datafyde/Guided-Project-Data-Heroes/assets/135570337/96693b40-07f5-43fe-9372-c5ffd95925dc)

The data was sourced from Kaggle and is about a hotel booking

## Data Inspection
Dataset shape: 21,996 rows and 32 columns <br>						
Missing values:	agent column has 3099	missiing values. The values were kept.	<br>	
	              company column had 20,691	missing values. The column was dropped to prevent skewness in the data.<br>			
Duplicates: Duplicates were ofund in the data and were addressed in Power Query	<br>
Outliers were discovered but were kept.	<br>	
The data was found to be inconsistent but the data types were consistent

## Data Cleaning
Merged the 2018, 2019, 2020 datasets<br>
Duplicates were removed <br>
NULL values were replaced with empty string<br>
Categorical data displayed as 1s and 0s were replaced with the appropriate text<br>
Created arrival date column <br>
Extracted specific date values from the reservation status date <br>

## Data Modeling
Created the different dimension tables:

#### Hotel DImension Table
duplicated final hotel data <br>
undid all previous transformation <br>
removed all columns except **hotel** <br>
created hotel ID column <br>

#### Location DImension Table
data was extracted from [statistic times](https://statisticstimes.com/geography/countries-by-continents.php). <br>
we cleaned the data, only  extracting the coliumns needed

#### Date DImension Table




This is the completed data model:
![Screenshot 2023-11-01 203348](https://github.com/Datafyde/Guided-Project-Data-Heroes/assets/135570337/095f77f6-5994-4905-bc1d-6b33fced0be3)


					

