# WebScraped-NASA-Exoplanet-EDA
Exploratory data analysis of NASA exoplanet data, including preprocessing, visualizations, correlation analysis, and outlier removal. Insights gained on exoplanet discovery trends, mass distribution, and correlations.

## Exploratory Data Analysis of NASA Exoplanet Data

This repository contains an exploratory data analysis (EDA) of a dataset on exoplanets. The dataset was collected via web scraping from NASA's exoplanet archive.

## Data Collection
The initial dataset was collected by web scraping NASA's exoplanet archive. The data includes information about various exoplanets, such as their name, distance from Earth, mass (in Jupiter masses), discovery date, and stellar magnitude.

## Data Preprocessing
The raw data was loaded into a Pandas DataFrame for analysis. The mass of the exoplanets, initially given in Jupiter masses, was converted to Earth masses to facilitate analysis.

## Data Analysis
The analysis included a range of techniques:

### Missing Value Analysis: 
I analyzed the dataset for missing values. Some missing values were found in the columns for distance, mass, and stellar magnitude.
### Descriptive Statistics: 
I computed summary statistics for the numerical variables, providing insights into their central tendency and dispersion.
### Visualizations:
I created several visualizations, including a scatterplot matrix, count plots, box plots, and scatter plots, to better understand the distribution of the variables and the relationships between them.
### Correlation Analysis: 
I computed a correlation matrix to investigate the relationships between the numerical variables. A strong positive correlation was observed between the distance of the exoplanets and their stellar magnitude.
### Outlier Analysis and Removal: 
I identified and removed outliers in the mass of the exoplanets using the Interquartile Range (IQR) method.

## Insights

Through this exploratory data analysis, I gained several insights into the dataset:

->The discovery of exoplanets has increased dramatically over the years, with the most discoveries made between 2014 and 2017.

->There is a strong positive correlation between the distance of an exoplanet and its stellar magnitude.

->Most exoplanets have a mass less than approximately 5000 Earth masses. After removing outliers, the maximum mass observed was around 2500 Earth masses.
