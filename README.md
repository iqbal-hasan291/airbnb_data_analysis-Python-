# Airbnb Exploratory Data Analysis (EDA) Project

This project involves an in-depth exploratory data analysis (EDA) of Airbnb listings data using Python. The aim is to uncover key insights about pricing, availability, room types, and host behaviors that can guide both Airbnb business decisions and travelers' choices.
![](AirBnB_image.webp)
---

## Objective

The goal of this project is to:
- Clean and preprocess raw Airbnb dataset
- Explore key features affecting pricing and popularity
- Visualize patterns, trends, and relationships across variables
- Generate business insights and recommendations
- Create a presentable portfolio project for resume/GitHub

---

## Goals

- Handle missing values and inconsistent data
- Perform univariate and bivariate analysis
- Generate impactful seaborn/matplotlib visualizations
- Identify trends in price, room type, availability, and reviews
- Prepare this as a resume project hosted on GitHub

---

## Dataset Description

The dataset contains Airbnb listings with the following key columns:
- `id`, `name`, `host_id`, `host_name`
- `neighbourhood_group`, `neighbourhood`
- `latitude`, `longitude`
- `room_type`, `price`, `minimum_nights`
- `number_of_reviews`, `last_review`, `reviews_per_month`
- `calculated_host_listings_count`, `availability_365`
- `rating`, `bedrooms`, `beds`, `baths`

Source: *Publicly available sample Airbnb data*

---

## Workflow & Steps

1. **Initial Exploration**
   - Dataset loading and structure check
   - Null value detection and column type correction

2. **Data Cleaning**
   - Converted `last_review` to datetime
   - Filled missing values (like `reviews_per_month`, `latitude`, `room_type`, etc.)
   - Removed price outliers for accurate visualizations

3. **Univariate Analysis**
   - Explored price, availability, reviews, room types
   - Used histograms and count plots

4. **Bivariate Analysis**
   - Explored relationships between price vs. room type, availability vs. rating, etc.
   - Used boxplots, scatterplots, and correlation heatmaps

5. **Data Visualization**
   - Used Seaborn and Matplotlib for all visualizations
   - Ensured clear labeling, legends, and presentation

---

## Key Visualizations

- 📦 **Boxplot**: Room Type vs Price  
- 📍 **Bar Plot**: Top 10 neighborhoods by number of listings  
- 💲 **Bar Plot**: Average price by neighborhood group  
- 🌐 **Scatterplot**: Availability vs Rating  
- 🔥 **Heatmap**: Correlation of all numeric variables  
- 🛏️ **Boxplot**: Bedrooms vs Price

---

## Key Insights

- **Entire homes/apartments** have significantly higher prices than shared/private rooms.
- Listings with **lower prices tend to receive more reviews**, suggesting higher booking volume.
- Certain neighborhoods (like `Downtown`, `Uptown`, etc.) dominate the market.
- Most hosts own only one listing, but a few **professional hosts** manage 10+ properties.
- Availability doesn't always correlate with high ratings — hosts should balance booking frequency with guest experience.
- Prices tend to increase with the **number of bedrooms** and **room type**.

---

## Conclusion

This analysis highlights how pricing, location, and listing type affect the success of an Airbnb listing. The insights can be valuable for:
- **Airbnb hosts**: to optimize pricing and listing quality
- **Travelers**: to find value-for-money options
- **Airbnb team**: to refine search, pricing, and recommendation algorithms

---

## Tools Used

- Python 
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Jupyter Notebook

---


