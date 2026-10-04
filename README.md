# Customer Bike Purchase Analysis

## Project Overview

This project analyzes customer bike purchase behavior using Power BI.

The goal was to understand which customer characteristics were associated with higher bike purchase rates and to turn the analysis into a clear, interactive dashboard.

This was also a hands-on learning project for me as I worked on connecting Power Query, DAX, measures, slicers, and visualizations into one complete analysis.

## Business Question

Which customer characteristics are associated with higher bike purchase rates?

The analysis focused on:

- Age Group
- Region
- Commute Distance
- Occupation
- Marital Status
- Number of Cars Owned

## Tools Used

- Power BI
- Power Query
- DAX
- Excel / CSV dataset

## Data Preparation

The dataset contained 1,000 customer records.

During data preparation, I:

- Reviewed missing values across multiple columns
- Replaced missing values in some categorical fields with `Unknown`
- Used the median for missing Income values
- Preserved some null values where there was not enough evidence to make a reasonable assumption
- Verified data types
- Checked for duplicate records
- Created an Age Group column
- Created a custom sort order for Commute Distance

## Key Measures

### Total Customers
Counts the total number of customers in the dataset.

### Bike Buyers
Counts customers where `Purchased Bike = Yes`.

### Purchase Rate

**Purchase Rate = Bike Buyers ÷ Total Customers**

The overall bike purchase rate was **48.10%**.

## Dashboard

The dashboard includes:

- Total Customers
- Bike Buyers
- Non Buyers
- Overall Purchase Rate
- Purchase Rate by Age Group
- Purchase Rate by Region
- Purchase Rate by Commute Distance
- Purchase Rate by Occupation
- Purchase Rate by Marital Status
- Purchase Rate by Number of Cars
- Interactive slicers
- Tooltips with customer and buyer counts
- Overall purchase-rate reference lines
- Key Insights section


## Key Insights

- The **Pacific region** had the highest regional purchase rate at **58.85%**, which was **10.75 percentage points above** the overall purchase rate.
- Customers with **0 cars** had a **61.76%** purchase rate.
- Customers commuting **2–5 miles** had the highest commute-based purchase rate at **58.64%**.
- Middle-aged customers had a higher purchase rate than younger and older customer groups.
- Purchase rates generally decreased for customers with longer commute distances.

## What I Learned

This project helped me understand that building a dashboard is not just about creating charts.

Some of my main learnings were:

- Start with business questions before selecting visuals
- Use rates instead of only counts when comparing groups of different sizes
- Check the number of customers behind a percentage before interpreting it
- Compare segment performance with an overall benchmark
- Avoid confusing association with causation
- Explore variables before deciding whether they are important
- Use dashboard design to make insights easier to understand

This project helped me move from learning Power BI features individually to understanding how they work together in a complete analysis.

## Files

- `Customer_Bike_Purchase_Analysis.pbix` - Power BI project file
- `Bike sales dashboard.png` - Final dashboard screenshot
- `bike_buyers.csv` - Dataset used for the analysis
