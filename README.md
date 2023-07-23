# Restaurant Recommendation Model

![Restaurant Recommendation Model](images/swiggy_ml_project.png)

## Introduction

This repository contains the code and documentation for the **Restaurant Recommendation Model**. The project involves collecting restaurant data from the Swiggy website using web scraping techniques, cleaning the data using Python and pandas, building a linear regression model to predict restaurant prices, and using logistic regression and random forest classifier models to predict restaurant locations based on cuisine and price. The project also includes an interactive webpage built using Streamlit library to provide user-friendly recommendations and insights about popular restaurants, cuisines, and prices.

## Data Collection

To collect restaurant data from Swiggy, we used **Selenium** and **BeautifulSoup** in Python. Selenium is a powerful web automation tool that allows us to interact with the Swiggy website, while BeautifulSoup helps in parsing the HTML content to extract relevant information.

## Data Cleaning

Once the data was collected, it underwent a data cleaning process using Python and pandas to handle missing values, remove duplicates, and ensure consistency in the data.

## Linear Regression Model for Price Prediction

We built a linear regression model to predict restaurant prices based on the given location and cuisine. This model allows us to estimate the price of a restaurant based on the selected features.

## Logistic Regression and Random Forest Classifier Models for Location Prediction

To predict restaurant locations based on cuisine and price, we used both logistic regression and random forest classifier models. After comparing the performance of both models, we found that the random forest classifier had higher accuracy and thus adapted it for location prediction.

## Interactive Webpage using Streamlit

We created an interactive webpage using the Streamlit library in Python. The webpage takes user inputs for location and cuisine and provides the following outputs:

1. Most popular restaurant in the selected area.
2. Most popular cuisine in the selected area.
3. Average price of restaurants in the selected area.
4. Restaurants that serve the selected cuisine in the area.

## Feedback Page

The interactive webpage also includes a feedback page where users can provide their feedback about the recommendations and overall experience. This feedback will help us improve the model and enhance user satisfaction in the future.

## Dependencies

The following Python libraries are used in this project:

- Selenium
- BeautifulSoup
- pandas
- scikit-learn
- Streamlit

## How to Use

To use this project, follow these steps:

1. Clone the repository: `git clone https://github.com/yourusername/swiggy-ml-prediction.git`
2. Install the required dependencies: `pip install -r requirements.txt`
3. Run the data collection script: `python data_collection.py`
4. Run the data cleaning script: `python data_cleaning.py`
5. Run the linear regression model script: `python linear_regression.py`
6. Run the logistic regression and random forest classifier model script: `python random_forest_classifier.py`
7. Start the Streamlit web application: `streamlit run main.py`

## Contributing

We welcome contributions to this project! If you find any issues or have suggestions for improvement, please create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

We would like to thank Swiggy for providing the restaurant data, which made this recommendation model possible. Additionally, we acknowledge the open-source community for the valuable tools and libraries used in this project. Your feedback is essential for enhancing the project and user experience. Thank you for using our interactive webpage!
