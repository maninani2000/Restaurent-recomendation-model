# Restaurant Recommendation Model

![Screenshot (287)](https://github.com/maninani2000/Restaurent-recomendation-model/assets/133534027/12639afe-1d8b-4182-97e0-35abdde01320)


## Introduction

This repository contains the code and documentation for the **Restaurant Recommendation Model**. The project involves collecting restaurant data from the Swiggy website using web scraping techniques, cleaning the data using Python and pandas, building a linear regression model to predict restaurant prices, and using logistic regression and random forest classifier models to predict restaurant locations based on cuisine and price. The project also includes an interactive webpage built using Streamlit library to provide user-friendly recommendations and insights about popular restaurants, cuisines, and prices.

## Aim of the Project 
This project aims to utilize data scraped from Swiggy to create a machine learning model that predicts menu prices based on cuisine and location inputs. Additionally, a random forest classifier suggests optimal dining locations, while a Streamlit web interface enables user interaction and feedback for continuous model enhancement.

## Process Flow

1. Install the required dependencies:
    * import the required libraries like pandas,numpy,sklearn,beautfull soup,selenium
![Screenshot (290)](https://github.com/maninani2000/Restaurent-recomendation-model/assets/133534027/984ccf08-622c-45b6-9290-4c08e250ed69)
2. Run the data collection script:
    * Run the code for extracting the data using selenium and beautifullsoup libraies
![Screenshot (291)](https://github.com/maninani2000/Restaurent-recomendation-model/assets/133534027/217bd49b-08c6-4a67-9d96-a13968c1e7d3)
3. Run the data cleaning script:
     * Data cleaning involves removing noice from the dataset,handling missing values and dealing with duplicates.
     * The noice is replaced with relevent values
     * The null values in the categorical columns are replaced with mode of that column when it makes sense, the null values in the numerical columns are replaced with the median of that column.
     * Finally removed the duplicates
4. Run the linear regression model script:
      * Developed a linear regression model to predict menu item prices.
      * Objective is to estimate menu prices based on input features such as cuisine and location.
      * Achieved an R-squared (coefficient of determination) score of 0.7.
5. Run the logistic regression and random forest classifier model script:
      * After developing multiple models including Logistic Regression and Random Forest to predict the location, the Random Forest model stood out with an impressive accuracy of 87%.
      * Compared to the 35% accuracy achieved by the Linear Regression model, the Random Forest model demonstrates a significantly higher predictive power.
      * As part of future development, continuous monitoring and potential retraining of the model with fresh data can maintain its accuracy and relevance.
6. Start the Streamlit web application:
      * Deployed both the models which are developed to predict price and location in the webpage using stramlit library.
      * Made some attractive background colour effects for visual appeal.
      * Made a webpage to receive user feedback and connected it to an Excel sheet to store the data.

## Input Page

![image](https://github.com/maninani2000/Restaurent-recomendation-model/assets/133534027/bbd3c266-45bb-4cbd-bb14-d3f173b27538)


## Findings Page
  The webpage built to display the fallowing findings along with the predictions:-
1. Most popular restaurant in the selected area.
2. Most popular cuisine in the selected area.
3. Average price of restaurants in the selected area.
4. Restaurants that serve the selected cuisine in the area.

![image](https://github.com/maninani2000/Restaurent-recomendation-model/assets/133534027/1257ed9e-08d5-4371-8920-508e17284288)


## Feedback Page

The interactive webpage also includes a feedback page where users can provide their feedback about the recommendations and overall experience. This feedback will help us improve the model and enhance user satisfaction in the future.

![image](https://github.com/maninani2000/Restaurent-recomendation-model/assets/133534027/09ce6138-3694-49c6-b03f-6894c20fbbcf)

## Limitations and Future work
  1. Not enough data about users or items, making it difficult to give accurate recommendations.
      * Alternative data sources
  2. Struggle with updates in real-time, like new user preferences or changing item availability.
      * Adapt and update recommendations in real time.
  3. Handle sensitive user data, so we need to prioritize privacy.
      * Privacy-preserving techniques
  4. Not enough information about certain items, especially those that are not popular or niche.
      * Fill missing values by analyzing patterns in user-item interactions to estimate the unknown values.
  5. Make recommendations more understandable and transparent.
      * Build trust and understanding and take user feedback into account.
  6. Better ways to measure recommendation system performance.
      * Explore new evaluation metrics that consider user satisfaction, diversity, or long-term engagement

## <img src="https://github.com/yasmeenustad/Swiggy-data-Analysis/assets/112754746/2e256cec-1421-4c5f-9913-052a53dc470f" width="70" height="50"> Learnings:
   * Stream lit python library
   * Deploy Machine Learning Model in Webpage
   * Basic Knowledge of CSS
   * Basic Knowledge of HTML tag
   * Scraping data from Websites
   * Time Management
   * Team Work and Coordination.

## <img src="https://github.com/yasmeenustad/Swiggy-data-Analysis/assets/112754746/1334f205-b4ce-4125-b71f-a38637dec197" width="70" height="50" > Conlusions:

In summary, the project achieved its objective of assisting users in making informed dining choices by scraping Swiggy data and employing advanced models like Linear Regression, Logistic Regression, and Random Forest. The Random Forest model outshone others with an impressive 87% accuracy in predicting menu prices and suggesting suitable restaurants. The integration of a user-friendly Streamlit web interface facilitates easy interaction, while user feedback ensures ongoing refinement, making this project a powerful example of data-driven decision-making and technology integration.







