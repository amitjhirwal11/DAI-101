# DAI-101-Assignment-1

## *Project Title:*  
*DAI Assignment 1 - used car Dataset Analysis*  

## *Author:*  
*Amit meena - 23112014*  

## *Project Overview:*  
This project analyzes a used car dataset in which i analyse all about used car about their cylinder , engine and all the parts .  

## *Dataset:*  
The dataset consists of various used car details including:  
- *Numerical Features*: cylinder , engine ,  model , year.  
- *Categorical Features*: Outcomes (engine , cylinder )  

## *Workflow:*  

### *Data Cleaning:*  
- Handled missing or inconsistent values in the dataset.  
- Removed irrelevant columns that don't contribute to the analysis.  

### *Univariate Analysis:*  
- Distribution plots for numerical columns (fuel , model , condition).  
- Count plots for categorical columns (region Outcomes).  

### *Outlier Detection & Handling:*  
- Boxplots have been generated for numerical columns to visualize outliers.  
- Extreme outliers were removed using the Z-score method (Threshold = 3).  

### *Bivariate Analysis:*  
- *Correlation Heatmap* to visualize relationships between numerical variables.  
- *Pairplots* to explore feature interactions.  
- *Boxplots* for drive vs size Outcome.  
- *Barplots* for car type vs no. of listing.  

### *Additional Insights:*  
- *car type Trends Based on no. of listing*  
- *no. of listing vs title status Outcomes Analysis*  
- *car type Distribution Among well and Not well *  
- *Impact of car type on drive*  
- *Feature Engineering*: car type no. of listing Ratio 

## *Results:*  
The project provides comprehensive insights into car type and all about there conditions how they work in there different situation . 

## *Dependencies:*  
numpy
- pandas
- matplotlib
- scipy
- seaborn
