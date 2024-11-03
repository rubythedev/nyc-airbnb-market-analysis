# NYC Vacation Rental Market Analysis

## Project Overview
This project is a comprehensive analysis of the Manhattan vacation rental market using Airbnb data. The goal is to assist a consulting client in identifying profitable vacation rental investment opportunities by analyzing key data points related to neighborhood popularity, property sizes, occupancy rates, and potential revenue.

## Dataset
The dataset used for this analysis is the NYC Airbnb dataset, which includes information on listings, availability, and other relevant details. It contains multiple sheets (data dictionary, listings, calendar) that offer insights into current listings, reviews, and rental activities.

- **Data Source**: NYC Airbnb dataset
- **Key Sheets**: Data Dictionary, Listings, Calendar

## Project Link
[NYC Vacation Rental Market Analysis](https://docs.google.com/spreadsheets/d/1C-JBFrbFeeHaOa94HlIgMUcOBJkeSoNmVrSZIUx-bHg/edit?usp=sharing)

---

## Introduction
Manhattan’s vacation rental market offers diverse opportunities for real estate investment, yet determining the best neighborhoods and property types for high returns can be complex. Through this project, we analyze Airbnb data to uncover insights that can guide investment decisions. The analysis covers popular neighborhoods, preferred property sizes, occupancy trends, and estimated revenues, ultimately providing a data-driven recommendation for investment.

---

## Project Objectives
1. Identify the most popular neighborhoods in Manhattan for vacation rentals.
2. Determine the optimal property size to target for investment.
3. Calculate occupancy rates and average prices across properties.
4. Estimate annual revenue potential based on occupancy and price trends.
5. Offer recommendations for property investment based on data insights.

---

## Methodology
The project methodology follows these steps:

1. **Data Exploration and Cleaning**: Reviewed, filtered, and cleaned the dataset to ensure relevant data was used in the analysis.
2. **Neighborhood Analysis**: Standardized neighborhood labels and analyzed reviews to find popular areas.
3. **Property Size Analysis**: Identified the most rented property sizes and filtered properties with at least one review in the last 12 months.
4. **Occupancy Calculation**: Used calendar data to calculate occupancy rates by creating a new `occupied` column.
5. **Revenue Estimation**: Calculated potential revenue based on average occupancy rates and prices for top-performing neighborhoods.
6. **Executive Summary and Recommendations**: Compiled key findings and provided actionable insights.

---

## Visual Representations
Below are some of the key visualizations generated from this analysis:

1. **Top 10 Neighborhoods by Popularity**  
   <img src="https://github.com/rubythedev/nyc-airbnb-market-analysis/blob/main/popularitybyneighborhood.png" width="400">  
   _Fig 1: This chart shows the top 10 neighborhoods in Manhattan based on the number of reviews in the last 12 months._

2. **Occupancy Rate by Day of the Week**  
   <img src="https://github.com/rubythedev/nyc-airbnb-market-analysis/blob/main/occupancybydayofweek.png" width="400">  
   _Fig 2: This bar chart illustrates the average occupancy rates by day of the week, showing higher rental demand on specific days._

3. **Revenue Estimation for Optimal Investment Properties**  
   <img src="https://github.com/rubythedev/nyc-airbnb-market-analysis/blob/main/revenueestimation.png" width="400">  
   _Fig 3: This pivot table shows estimates of annual revenue for properties in the most popular neighborhoods with ideal property sizes._

---

## Key Findings
- **Popular Neighborhoods**: The Lower East Side, Hell's Kitchen, and Harlem are the top neighborhoods for vacation rentals based on review counts.
- **Optimal Property Size**: One-bedroom apartments are the most rented property type, especially in popular neighborhoods.
- **Occupancy Trends**: Higher occupancy rates are observed over weekends, with slight declines during weekdays.
- **Revenue Potential**: Properties in the most popular neighborhoods with consistent occupancy can achieve high annual revenues, making them attractive for investment.

---

## Conclusion
The analysis reveals that investing in one-bedroom apartments in popular neighborhoods like the Lower East Side and Hell's Kitchen can yield high occupancy and potential revenue. Occupancy rates tend to be higher on weekends, which can be beneficial for targeting short-term vacation rentals.

---

## Recommendations for Improvement
1. **Expand Dataset**: Consider additional years of data to analyze seasonal trends.
2. **Refine Occupancy Rate Estimation**: Utilize more accurate measures of occupancy if available, rather than relying solely on review counts.
3. **Market Segmentation**: Further segment the data by amenities offered to see if certain features increase occupancy and rental price.

---

## Future Directions
1. **Advanced Analysis of Amenities**: Explore the impact of specific amenities (e.g., doorman, instant booking) on occupancy rates and revenue.
2. **Predictive Modeling**: Implement predictive analytics to forecast high-demand periods and adjust pricing strategies accordingly.
3. **Competitor Analysis**: Compare other rental platforms to provide a holistic view of the vacation rental market in Manhattan.

---

This analysis provides a foundational understanding of the Manhattan vacation rental market, enabling data-driven investment decisions for future property acquisitions.
