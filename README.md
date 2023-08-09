# Data Cleaning - NashvilleHousing
This project was undertaken to demonstrate data-cleaning skills using SQL. The focus is cleaning the database and preparing it for further analysis. This project does not include the analysis itself. 
## The Dataset
The dataset used was obtained from a GitHub user. [See Dataset](https://github.com/AlexTheAnalyst/PortfolioProjects/blob/main/Nashville%20Housing%20Data%20for%20Data%20Cleaning.xlsx)
The dataset was downloaded and imported into Microsoft SSMS. 
## Data Cleaning and Transformation
The cleaning and transformation of the dataset include the following
1. Standardization of the date format using the Convert Date function.
2. Population of the Property Address column where it is null and exists in a corresponding parcel ID.
3. Breaking out Address into individual columns (Address, City, State) for property address and owner address.
4. Changed Y and N to Yes and No in the "Sold as Vacant" Field.
5. Removal of Duplicates using CTE
6. Removing unused columns.
View [SQL Script](https://github.com/Tomianne/NashvilleHousing/blob/main/Nashville%20Housing%20Data%20Cleaning.sql)
