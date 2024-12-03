# Clustering-Project: $10 Million Distribution among countries
## Project Overview
This project aims to categorize countries based on socio-economic and health factors to evaluate their overall level of development. The categorization will help prioritize aid distribution to countries in dire need, ensuring strategic and effective utilization of available resources.

## Objective
To assist HELP International, an international humanitarian NGO, in identifying countries that require immediate aid by categorizing them based on key development indicators.

## About HELP International 
HELP International is a global non-governmental organization committed to:
* Fighting poverty.
* Providing basic amenities to underserved populations.
* Delivering relief during natural disasters and other crises.

## Problem Statement 
HELP International has raised $10 million to support its mission. The CEO of the NGO must decide how to allocate these funds strategically to maximize their impact.

As a Data Scientist, your responsibility is to:
* Analyze socio-economic and health factors to evaluate each country’s development level.
* Categorize countries into meaningful groups.
* Recommend the countries that should be prioritized for aid based on the analysis.

## Steps Performed 
### 1. Data Preprocessing 
* Handled missing values by imputing them where appropriate.
* Treated outliers to ensure data consistency and reliability.
* Scaled the data for uniformity to improve clustering results.

### 2. Descriptive Analysis
* Conducted exploratory data analysis (EDA) to understand patterns and distributions within the data.
* Examined correlations and key trends among socio-economic and health indicators.

### 3. Dimensionality Reduction 
* Applied Principal Component Analysis (PCA) to reduce dimensionality for better clustering performance and visualization.

### 4. Clustering 
* Experimented with multiple clustering techniques, including:
  * K-Means
  * Hierarchical Clustering
  * DBSCAN
* Identified K-Means clustering as the most effective approach, achieving a better silhouette score, indicating well-defined clusters.

## Results and Recommendations 
* The countries were categorized into groups based on development levels.
* Specific clusters were identified that represent countries in the direst need of aid.
* Recommendations for priority countries were provided to the CEO for effective fund allocation.

## Future Scope 
* Include more indicators to refine the analysis (e.g., environmental or governance metrics).
* Incorporate time-series data to track development trends over time.
* Develop a dashboard to visualize the categorization dynamically.
