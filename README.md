# Seattle_Airbnb_Listings_Comprehensive-Analysis-of-Listings

![Github](https://medium.com/@msmohan.kumar2/seattle-airbnb-listings-comprehensive-analysis-of-listings-trends-and-insights-e946ad20ec67)
![main page](https://github.com/msmohankumar/House_Price_Prediction/assets/153971484/b6921762-fce8-43b2-bcc7-139b4d1e52a8)

## Project Motivation
### This project is part of the Udacity Data Scientists Nanodegree Program. I utilized the Seattle Airbnb Dataset, which describes the listing activities of homestays in Seattle, WA. The original dataset can be found here

## Overview

This project investigates factors influencing Airbnb listing prices in Seattle. We leverage data from Kaggle to perform exploratory analysis and build machine learning models for price prediction.

**Key Questions:**

* What attracts guests the most when renting a property?
* What are the most influential features of the dataset for estimating the price of a listing?
* What is the impact of listings' proximity to Seattle Downtown in terms of price?

# Methods Used

## Data Collection and Preprocessing

- **Data Collection:** The dataset was obtained from Kaggle, specifically the Seattle Airbnb dataset.
- **Data Cleaning:** The dataset underwent cleaning processes to handle missing values, inconsistencies, and outliers.
- **Feature Engineering:** Additional features were engineered, such as amenities parsing and calculating distances from downtown Seattle.
- **Data Transformation:** Categorical variables were encoded, and numerical features were scaled to prepare the data for modeling.

## Exploratory Data Analysis (EDA)

- **Data Visualization:** Seaborn and Matplotlib.pyplot were used to create visualizations to explore relationships between variables, distribution of features, and patterns in the data.
- **Descriptive Statistics:** Summary statistics and frequency distributions were calculated to gain insights into the dataset.

## Machine Learning Modeling

- **Linear Regression:** Sklearn's Linear Regression model was employed to predict listing prices based on various features.
- **Feature Importance:** Coefficient weights were analyzed to identify the most influential features in predicting listing prices.
- **Model Evaluation:** The model's performance was assessed using metrics such as Mean Absolute Error (MAE) and R-squared.

## Interpretation and Conclusion

- **Interpreting Results:** Findings from the analysis were interpreted to draw conclusions and insights into the Seattle Airbnb market.
- **Recommendations:** Based on the analysis, recommendations were made for Airbnb hosts and potential guests to optimize their experiences.



## Getting Started

**Prerequisites:**

* Anaconda and Jupyter Notebook (https://www.anaconda.com/)


**Project Structure:**

* Airbnb-Data-Science-Project/
*
* ├── data/
* │  ├── calendar.zip        # Calendar data from Kaggle
* │  ├── listings.zip        # Listings data from Kaggle
* │  └── reviews.zip          # Reviews data from Kaggle
* ├── notebooks/
* │  ├── Jupyter note processed data  # Feature/amenity analysis
* ├── README.md              # Project documentation
* ├── LICENSE                # License information


**Run the Analysis:**

1. Clone this repository.
2. Open Jupyter Notebook and navigate to the project directory.
3. Open the Jupyter Notebook files :
    * Seattle_Airbnb_Listings_Comprehensive-Analysis-of-Listings.ipynb
    

## Technologies Used

* **Programming Language:** Python 3 (executed in Jupyter Notebook)
* **Data Manipulation:** Pandas
* **Machine Learning:** scikit-learn
* **Visualization:** Matplotlib


## Developers

* M S Mohan Kumar
