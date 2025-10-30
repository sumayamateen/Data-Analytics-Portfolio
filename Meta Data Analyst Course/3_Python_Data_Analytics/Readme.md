# Pet Store Transactions Analysis

![Python](https://img.shields.io/badge/Python-Data_Cleaning-green)
![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-blue)
![Seaborn](https://img.shields.io/badge/Seaborn-Data_Visualization-purple)
![Statistics](https://img.shields.io/badge/Statistics-Exploratory_Analysis-orange)
![Framework](https://img.shields.io/badge/Framework-OSEMN-ff69b4)
A comprehensive data analysis project following the OSEMN (Obtain, Scrub, Explore, Model, Interpret) framework to analyze pet store transaction data and derive actionable business insights.

## Project Overview

This project analyzes pet store transaction data to understand sales patterns, product performance, and customer purchasing behavior. The analysis helps identify which product categories drive the most sales and provides recommendations for inventory optimization and business strategy.

## Dataset

The dataset (`transactions-pet_store.csv`) contains 2,903 transaction records with the following features:

- **Date**: Transaction date
- **Order_Number**: Unique order identifier
- **Customer_ID**: Customer identifier
- **Product_Name**: Name of purchased product
- **SKU**: Product stock keeping unit
- **Price**: Product price
- **Size**: Product size (removed due to high missing values)
- **Quantity**: Number of items purchased
- **Product_Category**: Category of product (treat, toy, bedding, food)
- **Product_Line**: Type of pet (cat, dog)

## Analysis Framework

### 1. **Data Scrubbing (Cleaning)**
- Removed rows with missing product names or categories
- Cleaned price outliers using quantile filtering
- Dropped columns with excessive missing values (>500)
- Handled missing customer IDs by filling with "Unknown"

### **Data Exploration**
- Created `Subtotal` column (Price × Quantity)
- Identified most popular product categories by sales volume
- Analyzed product categories with highest median prices
- Generated key business metrics and insights

### **Data Visualization**
- Horizontal bar plots comparing sales across product categories
- Enhanced visualizations for stakeholder presentations
- Data labels and clear annotations for better interpretation

## Key Findings

### Sales Performance by Category
| Product Line | Most Popular Category (Quantity) | Highest Priced Category |
|--------------|----------------------------------|-------------------------|
| **Cat**      | treats                           | bedding                 |
| **Dog**      | bedding                          | toys                    |

### Business Insights
- **Cat products dominate sales**, particularly toys and treats
- **Dog bedding** performs strongly in the dog product line
- Visual analysis reveals clear patterns in customer purchasing behavior
- Recommendations consider both sales volume and pricing strategies
