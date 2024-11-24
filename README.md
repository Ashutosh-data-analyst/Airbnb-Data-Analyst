# Airbnb-Data-Analyst
Data Analyst project using **Python**, **Numpy**, **Pandas**, **Seaborn** and **Matplotlib**

## Project Overview

This project conducts Exploratory Data Analysis (EDA) on New York Airbnb data to identify trends and patterns in rental listings. It utilizes libraries such as Pandas, NumPy, Matplotlib, and Seaborn for data cleaning, visualization, and analysis.

## Objective
The objectives of this project are to:

1. Examine room types, pricing trends, and availability across various neighborhoods.
2. Analyze host behavior and listing patterns.
3. Identify potential price outliers.
4. Offer insights and recommendations for both guests and hosts.

## Dataset
For Dataset **[Click Here](https://github.com/Ashutosh-data-analyst/Airbnb-Data-Analyst/blob/main/datasets.csv)**:

The dataset including:

- **id**: Unique identifier for each listing
- **name**: Title of the Airbnb listing
- **host_name**: Name of the host
- **neighborhood_group**: Group (borough) where the listing is located
- **latitude/longitude**: Geolocation of listings
- **price**: Nightly rental price
- **room_type**: Type of accommodation (e.g., entire home, private room)
- **reviews_per_month**: Average monthly reviews for the listing
- **availability_365**: Number of available days in the year

## Steps:

### 1. Data Cleaning
- **Handle Missing Data**: Addressed null values in the price, neighborhood, and beds columns.
- **Remove Outliers**: Capped prices above $1,000 to prevent skewed visualizations.

### 2. EDA (Exploratory Data Analysis)
1. **Room type distribution**:
   - Visualized the count of each room type using Histogram plots.
   - Identified that **"Entire homes/apartments"** is the most common room type.

2. **Neighborhood group insights**:
   - Analyzed price variations with neighbourhood group of each room types.
   - **Manhattan** had the highest average prices.

3. **Availability trends**:
   - Used **Heatmaps** to show correlations among price, availability_365, number_of_reviews, and beds.

4. **Price distribution:**
   - Used **Histograms** to show the distribution of prices.
   - Majority of the listings were priced between **$50 - $300**.

5. **Location and Review Dependency**:
   - Used **Scatter Plot** and find relation between Price and Number of review according to Locations.
   - Identified that **Manhattan** have maximumn number of reviews.

6. **Review behavior**:
   - Used **Pair plots** to show relationships between number of reviews, price, and availability.

### 3.  Data Visualization
- **Pairplot**: To see correlations among price, availability, and number of reviews.
- **Heatmap**: Showing correlations among numerical features.
- **Histograms and Boxplots**: To detect outliers in price.
- **Bar Charts**: Displaying room types and neighborhood group distributions.
   
## Key Findings and Insights

### 1. Price Trends:
 - **Manhattan** features the most expensive listings, with Brooklyn coming in second.
 - **Entire homes/apartments** are significantly more expensive than private or shared rooms.
### 2.
### 3.
### 4.
### 5. 
