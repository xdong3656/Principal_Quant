
# Principal Quant Execise

Data visualization and anomaly detection


## Authors

- [@xdong3656](https://github.com/xdong3656)



## Demo

Project Title: Principal Quant Execise.

Project Description: Data visualization and anomaly detection.

Table of Contents: 
     
     1. Instructions
     2. Data Description and assumptions
     3. Data Cleaning
     4. Data visualization
     5. Anomaly Detection

Installation Instructions: Install all the packages with the corresponding version, load the data and run the code.

Features: [Feature info](https://github.com/xdong3656/Principal_Quant/blob/main/features.xlsx)





## Project

#### Instructions

1. Set-Up: Make sure all packages are install with the same versions of the project. No configuration file is needed.

2. Running the Script: follow the steps of the code topdown.

3. Input Requirements: Download the data to google colab or local depository.

4. Output Description: output variable list in first part and the cleaned dataset in the second part.


#### Data Description and assumptions

Original data contains: 551 columns: DP03_0001E to fips
300 in float64 format, 49 in int64 format and 2 in object format. 68 data instances in total.

Data assumptions:

1. Independence assumption: Assume that the observations or measurements for each county are independent of each other.

2. Outlier detection assumption: Assume that the majority of the data points are "normal" or non-anomalous, and that outliers are relatively rare occurrences.

3. Feature scaling assumption: The numerical variables are scaled or standardized.

#### Data Cleaning

Delete 91 features which are completely missing. Impute mean value to the one missing in DP03_0002E and created missing indicator.

#### Data Visualization

Transpose data and get correlation matrix:
![correlation matrix of data after standardization](https://github.com/xdong3656/Principal_Quant/blob/main/Correlation_matrix.png)

Transpose data and get boxplot:
![Boxplot of data after standardization](https://github.com/xdong3656/Principal_Quant/blob/main/boxplot.png)

#### Anomaly Detection

Outliers visualization:


![Projection to first and second PC](https://github.com/xdong3656/Principal_Quant/blob/main/Outliers_12.png)

![Projection to first and third PC](https://github.com/xdong3656/Principal_Quant/blob/main/Outliers_13.png)

![Projection to first and fourth PC](https://github.com/xdong3656/Principal_Quant/blob/main/Outliers_14.png)

![Projection to second and third PC](https://github.com/xdong3656/Principal_Quant/blob/main/Outliers_23.png)

![Projection to second and fourth PC](https://github.com/xdong3656/Principal_Quant/blob/main/Outliers_24.png)

![Projection to third and fourth PC](https://github.com/xdong3656/Principal_Quant/blob/main/Outliers_34.png)





