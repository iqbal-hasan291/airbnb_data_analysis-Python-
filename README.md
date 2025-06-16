# Airbnb Exploratory Data Analysis (EDA) Project

This project involves an in-depth exploratory data analysis (EDA) of Airbnb listings data using Python. The aim is to uncover key insights about pricing, availability, room types, and host behaviors that can guide both Airbnb business decisions and travelers' choices.

![](https://github.com/iqbal-hasan291/airbnb_data_analysis-Python-/blob/c1fc59a26a484f33701b8a0ec3ebd64ff3d02f37/AirBnB_image.webp)
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


---

## Tools Used

![](https://github.com/iqbal-hasan291/airbnb_data_analysis-Python-/blob/970df29b779e27632f731f51d8c10935ad1497cf/image/_-%20visual%20selection%20(4).png)

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
   - Explored price, availability, room types etc.
   - Used histograms and count plots ,boxplot

4. **Bivariate Analysis**
   - Explored relationships between price vs. room type, availability vs. rating, etc.
   - Used boxplots, scatterplots, and  heatmaps

5. **Data Visualization**
   - Used Seaborn and Matplotlib for all visualizations
   - Ensured clear labeling, legends, and presentation


![](https://github.com/iqbal-hasan291/airbnb_data_analysis-Python-/blob/970df29b779e27632f731f51d8c10935ad1497cf/image/_-%20visual%20selection%20(3).png)

---

## Key Visualizations

-  **price distribution by frequency **
 
   ![](https://github.com/iqbal-hasan291/airbnb_data_analysis-Python-/blob/08966c1cf2d6d2ca6dfabe0dd9f6c5c2622f9206/image/image_1.png)
   
-  **Price Distribution by Room Type**
  
   ![](https://github.com/iqbal-hasan291/airbnb_data_analysis-Python-/blob/08966c1cf2d6d2ca6dfabe0dd9f6c5c2622f9206/image/image_2.png)
   
-  Insight: Understand which room types (e.g. entire home, private room) are more expensive.
  
-  **Average Price by Neighbourhood Group**
  
   ![](https://github.com/iqbal-hasan291/airbnb_data_analysis-Python-/blob/08966c1cf2d6d2ca6dfabe0dd9f6c5c2622f9206/image/image_3.png)
   
-  Insight: Identify hot rental zones—helpful for market expansion.
  
-  **Top Neighbourhoods by Number of Listings**
   
   ![](https://github.com/iqbal-hasan291/airbnb_data_analysis-Python-/blob/08966c1cf2d6d2ca6dfabe0dd9f6c5c2622f9206/image/image_4.png)
  
-  Insight: Show price variations across city regions.
  
-  **Relationship Between Number of Reviews and Price**
  
   ![](https://github.com/iqbal-hasan291/airbnb_data_analysis-Python-/blob/08966c1cf2d6d2ca6dfabe0dd9f6c5c2622f9206/image/image_5.png)
  
-  Insight: Check if cheaper listings get more reviews (volume strategy).
  
-  **Availability vs. Rating**
   
   ![]( https://github.com/iqbal-hasan291/airbnb_data_analysis-Python-/blob/08966c1cf2d6d2ca6dfabe0dd9f6c5c2622f9206/image/image_6.png)
   
-  Insight: Are higher-rated listings more or less available?
   
-  **Host Listing Count Analysis**
  
   ![](https://github.com/iqbal-hasan291/airbnb_data_analysis-Python-/blob/08966c1cf2d6d2ca6dfabe0dd9f6c5c2622f9206/image/image_7.png)
  
- Insight: Help customers understand pricing based on space offered.

-  **Bedroom vs Price Heatmap**
  
   ![](https://github.com/iqbal-hasan291/airbnb_data_analysis-Python-/blob/08966c1cf2d6d2ca6dfabe0dd9f6c5c2622f9206/image/image_8.png)
  
-  Insight: Help customers understand pricing based on space offered.
  
-  **Geographic Distribution**
  
   ![](https://github.com/iqbal-hasan291/airbnb_data_analysis-Python-/blob/08966c1cf2d6d2ca6dfabe0dd9f6c5c2622f9206/image/image_9.png) 

---

## Conclusion

This analysis highlights how pricing, location, and listing type affect the success of an Airbnb listing. The insights can be valuable for:
- **Airbnb hosts**: to optimize pricing and listing quality
- **Travelers**: to find value-for-money options
- **Airbnb team**: to refine search, pricing, and recommendation algorithms

---





