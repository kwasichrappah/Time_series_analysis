# Time Series Regression Analysis for Corporation Favorita, a large Ecuadorian-based grocery retailer

## Overview
Corporation Favorita, a large Ecuadorian-based grocery retailer,wants to ensure that it always has the right quantity of products in stock. To do this, I have been tasked to build a series of machine learning models to forecast the demand of products in various store locations and the marketing and sales team have provided me with some data to aid this endeavor. 

This project aims to forecast sales for the company using CRISP-DM.


## Problem Statement
The goal of this project is to develop forecasting models both statistical and machine learning that can forecast sales for Corporation Favorita in order to always have the right quantity of products in stock. By forecasting sales, the company can stock what is needed at appreciable quantities in the right stores to reduce locked capital in goods and have the more products where customers are most likely to patronize.

## Dataset
The dataset used for this project contains historical information about sales from all the shops from 2013 to 2017 and includes features such as:
- store_nbr
- store location
- Product family
- Product promotion
- Sales
- Crude oil prices within the specified period
- Holidays within the specified period (whether transferred or not)

## Project Structure
- **data/**: Contains the dataset files.
- **notebook/**: Jupyter notebook for data exploration, preprocessing, and model development.`
- **models/**: Saved machine learning tuned and non-tuned models.
- **README.md**: Project overview and instructions.

## Getting Started
1. Clone the repository:

   git clone https://github.com/kwasichrappah/Time_series_analysis.git 

   cd Time_series_analysis
2. Install dependencies:

   pip install -r requirements.txt

3. Explore the Jupyter notebooks in the `notebook/` directory for data analysis and model development.
4. Run the scripts in the `src/` directory for model deployment or further analysis.

## Dependencies
- Python 3.x
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- auto_arima
- Jupyter Notebook

## Data analysis 
- Data cleaning
- Exploratory data analysis 
- Analytical questions 

## Models
- Auto-arima
- Exponential Smoothening
- SVR 
- XGBoost


## Model Evaluation
We evaluate the performance of the machine learning models using metrics such as root mean square error,mean absolute error,mean absolute percentage error. Backtesting and Hyperparameter tuning techniques are used to optimize model performance.

## Deployment
The trained machine learning model can be deployed using the scripts provided. This allows daily sales forecast based on new data.


<!-- AUTHOR -->

## 👥 Authors <a name="author"></a>

🕵🏽‍♀️ **Emmanuel Chrappah**

-  Github:[Profile](https://github.com/kwasichrappah "Emmanuel Chrappah")
-  Email:[Email](mailto:emmanuel.chrappah@azubiafrica.org?subject=Hi "Hi!")
- Twitter: [Twitter Handle](https://twitter.com/jaychraps)
- LinkedIn: [LinkedIn Profile](https://www.linkedin.com/in/emmanuel-chrappah-61115813b/)


##  Contributions 

Contributions, issues, and feature requests are welcome!


## ⭐️ Show your support
If you like this project kindly show some love, give it a 🌟 **STAR** 🌟

## License
This project is licensed under the MIT License - see the LICENSE file for details.




