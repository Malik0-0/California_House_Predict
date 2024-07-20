<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
      <ul>
        <li><a href="#installation">Installation</a></li>
      </ul>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## Background of the California Housing Price Dataset

The California Housing dataset was derived from the 1990 U.S. Census. It contains information on various housing and demographic characteristics of California districts, often referred to as block groups, the smallest geographical unit for which the U.S. Census Bureau publishes sample data. This dataset is widely used for regression tasks and machine learning applications, particularly for predicting median house values based on different features.

### **Overview of the Dataset**

The dataset consists of 14,448 entries and 10 columns. Here are the descriptions of the columns:
- **longitude**: A float value representing the longitudinal coordinate of the district.
- **latitude**: A float value representing the latitudinal coordinate of the district.
- **housing_median_age**: A float value indicating the median age of the houses in the district.
- **total_rooms**: A float value indicating the total number of rooms in all houses within the district.
- **total_bedrooms**: A float value indicating the total number of bedrooms in all houses within the district.
- **population**:  A float value indicating the total population of the district.
- **households**: A float value indicating the total number of households in the district.
- **median_income**: A float value indicating the median income of the district's residents, scaled in tens of thousands of dollars.
- **ocean_proximity**: A categorical value indicating the district's proximity to the ocean. The categories include:
    - "NEAR BAY"
    - "<1H OCEAN"
    - "INLAND"
    - "NEAR OCEAN"
    - "ISLAND"
- **median_house_value**: A float value indicating the median house value for the district, scaled in hundreds of thousands of dollars. (the target variable).

### Key Insights
- **Geographical Distribution**: The dataset includes geographical coordinates (latitude and longitude) which can be used to plot and analyze the spatial distribution of house values and other attributes across California.
- **Ocean Proximity**: This categorical feature indicates the district's proximity to the ocean and includes categories like "NEAR BAY", "<1H OCEAN", "INLAND", "NEAR OCEAN", and "ISLAND". It is useful for examining the influence of proximity to water bodies on house prices.
- **Demographic and Housing Attributes**: Attributes such as median income, house age, total rooms, and population provide insights into the demographic and housing characteristics of each district, which are crucial for predictive modeling.

## **Business Problem and Goals**

### Business Problem

The **real estate market in California is highly dynamic** and **influenced by numerous factors** such as location, socioeconomic status, housing characteristics, and proximity to amenities like the ocean. **Accurate prediction of house prices** is crucial for various stakeholders, including real estate investors, home buyers, policymakers, and financial institutions.

**Main Objective**: To predict median house values to help real estate investors identify potential high-value investment opportunities.

### Goals

1. **Develop a Predictive Model for House Prices**:
   - **Objective**: Build and evaluate different regression models to predict the median house value in California based on the available dataset.
   - **Outcome**: Identify the best-performing model that provides accurate and reliable predictions of house prices.

2. **Analyze Key Factors Influencing House Prices**:
   - **Objective**: Perform feature importance analysis to understand which factors most significantly impact house prices.
   - **Outcome**: Gain insights into the primary drivers of house prices, such as proximity to the ocean, median income, and housing characteristics.

3. **Optimize Data Handling Techniques**:
   - **Objective**: Implement and compare various data preprocessing techniques, including outlier handling, missing value imputation, and data transformation, to enhance model performance.
   - **Outcome**: Determine the most effective preprocessing methods that improve model accuracy and robustness.

4. **Evaluate Model Performance Using Multiple Metrics**:
   - **Objective**: Assess the models using a comprehensive set of evaluation metrics, including MAE, MSE, RMSE, MAPE, RMSPE, and R-squared.
   - **Outcome**: Ensure a thorough evaluation to select the model that balances accuracy, interpretability, and computational efficiency.

5. **Provide Actionable Insights for Stakeholders**:
   - **Objective**: Translate model results into actionable insights for stakeholders such as real estate investors, home buyers, and policymakers.
   - **Outcome**: Enable stakeholders to make data-driven decisions regarding real estate investments, pricing strategies, and market analysis.
   - 
### Built With

This project was completely built using the tools:

* Python
* Pandas Library
* Seaborn Library
* Matplotlib Library
* Scikit-learn
* Google Cloud

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/Malik0-0/California_House_Predict.git 
   ```

## Contact

Malik Alrasyid Basori - malikalrasyidbasori.1@gmail.com

Github Link: https://github.com/Malik0-0
