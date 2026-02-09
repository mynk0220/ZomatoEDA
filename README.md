# ZomatoEDA
The primary objective of this project is to perform an Exploratory Data Analysis (EDA) on Indian restaurant data sourced from Zomato in order to understand:
- Restaurant distribution across cities
- Customer preferences and rating patterns
- Factors influencing restaurant ratings and popularity
- Pricing trends and service availability (online delivery, table booking)
The analysis aims to convert raw restaurant data into actionable business insights that can help food-tech companies, restaurant owners, and investors make informed decisions.

## Dataset Overview:
The dataset contains detailed information about restaurants listed on Zomato across multiple Indian cities.

Key Columns:
- Restaurant Name – Name of the restaurant
- City / Location – Geographic location of the restaurant
- Cuisines – Types of cuisines offered
- Average Cost for Two – Approximate dining cost for two people
- Aggregate Rating – Average customer rating
- Rating Color / Text – Rating category representation
- Votes – Number of user reviews
- Online Delivery – Availability of online food delivery
- Table Booking – Availability of table reservation

# Techniques & Tools Used:
## Data Cleaning:
- Handling missing and null values
- Removing duplicates
- Standardizing categorical columns

## Exploratory Data Analysis (EDA)
- Univariate analysis (distribution of ratings, cost, votes)
- Bivariate analysis (ratings vs cost, ratings vs services)
- City-wise and cuisine-wise aggregations

## Visualization

- Bar charts for city & cuisine distribution
- Histograms for rating and cost distribution
- Box plots for cost vs ratings
- Count plots for service availability

## Libraries Used:
- Pandas – Data manipulation
- NumPy – Numerical operations
- Matplotlib – Data visualization
- Seaborn – Advanced statistical plots

## Key Insights:
- Metro cities dominate the restaurant listings, indicating higher food-tech penetration.
- North Indian and Chinese cuisines are the most commonly offered.
- Restaurants with online delivery generally receive more customer engagement.
- Higher pricing does not guarantee better ratings.
- Restaurants with moderate pricing and consistent service quality receive the best ratings.
- Availability of table booking is more common in premium restaurants.

# Business Recommendations
-Focus on popular cuisines while introducing niche menu options.
-Maintain affordable pricing without compromising food quality.
-Enable online delivery to increase reach and customer engagement.

## For Food-Tech Platforms
- Promote mid-range restaurants with high ratings.
- Improve visibility for high-performing restaurants in non-metro cities.
- Use ratings and votes together for recommendation algorithms.

## For Investors & Analysts:
- Metro cities remain high-opportunity markets, but Tier-2 cities show growth potential.
- Cloud kitchens and delivery-focused models can yield strong ROI.

# Conclusion:
This project demonstrates how structured EDA can uncover meaningful insights from real-world restaurant data. The findings can support strategic decisions in restaurant operations, marketing, and platform optimization.
