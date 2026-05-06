# Module-11_Assignment-11-1
Required Assignment 11.1: What Drives the Price of a Car? The goal is to understand what factors make a car more or less expensive. As a result of the analysis, it should provide clear recommendations to the client—a used car dealership—as to what consumers value in a used car.

The GitHub Link : https://github.com/kimkok-UCBerkeleyHaas/Module-11_Assignment-11-1/

**What Drives the Price of a Used Car?**

An Analysis of 426,000 Used Car Listings using the CRISP-DM Framework. 

**Executive Summary**

This project analyzes a dataset of 426,000 used car listings to identify the key features that influence vehicle pricing. By understanding these "price drivers," used car dealerships can strategically fine-tune their inventory to maximize profit margins and turnover rates.

**The CRISP-DM Process**

To ensure a rigorous and repeatable analysis, this project follows the CRISP-DM (Cross-Industry Standard Process for Data Mining) methodology:  
- Business Understanding: Defining the goal from a dealer's perspective—identifying what consumers value most.  
- Data Understanding: Exploring the Kaggle dataset to identify trends, missing values, and data quality issues.  
- Data Preparation: Cleaning data, removing price/odometer outliers, and encoding categorical variables for modeling.  
- Modeling: Implementing Linear Regression, Ridge, and Lasso models to predict prices.  
- Evaluation: Identifying the most accurate model and interpreting coefficients to determine price drivers.  
- Deployment: Communicating actionable insights to the dealership.  

**Key Findings & Recommendations**

Note: Update these bullets with the specific coefficients found in notebook. 
- Mileage Matters: For every 1,000 miles added to the odometer, the average resale value drops by approximately $X.  
- Age vs. Value: Cars newer than 10 years maintain their value significantly better than older models, with the steepest decline occurring after year 12.  
- Manufacturer Impact: Brands like [Brand A] and [Brand B] command a premium in the used market compared to [Brand C].  
- Fuel Efficiency: Diesel and Hybrid vehicles are currently trending at a higher price point than standard gasoline engines for specific vehicle types.  

**Inventory Recommendations for the Dealer:** 

- Target High-Value Segments: Prioritize the acquisition of [Vehicle Type] with fewer than [X] miles.  
- Avoid High-Depreciation Features: Vehicles with [Specific Feature, e.g., Salvage Titles] correlate with significantly lower margins and longer time-on-lot.  
