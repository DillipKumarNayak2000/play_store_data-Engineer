# Google Play Store Data Analysis
This project focuses on analyzing the Google Play Store dataset to extract insights about app performance, user reviews, and pricing trends. Using various data transformation techniques, we prepare the dataset for advanced analysis.

## Project Overview
The goal of this project is to:

* Clean and preprocess the data.
* Analyze key app attributes like reviews, installs, and pricing.
* Gain insights into factors affecting app success.
## Dataset
The dataset includes information such as:
Data = https://github.com/DillipKumarNayak2000/play_store_data-Engineer/blob/main/googlestore.csv

* App Name: The title of the app.
* Category: The genre or type of app.
* Rating: The user rating for the app (out of 5).
* Reviews: The number of reviews an app has received.
* Installs: The total number of times the app has been installed.
* Price: The cost of the app (if not free).
## Data Preprocessing
We performed several preprocessing steps to clean and prepare the data for analysis:

* Cleaning the Installs Column: Removed any non-numeric characters to represent the number of installs as an integer.
* Cleaning the Price Column: Removed the $ sign from the price and converted it into a numerical format for analysis.
* Handling Missing Values: Addressed missing data in key columns like Rating and Reviews.
* Type Casting: Converted Reviews, Installs, and Price columns into integer data types for numerical analysis.

## Key Insights
* Rating Trends: Analyze which categories have the highest average ratings.
* Price Distribution: Examine the relationship between app prices and ratings or downloads.
* Installs and Reviews: Explore how the number of installs correlates with the number of reviews and ratings.
## Tools & Libraries
* Pandas and NumPy for data manipulation.
* PySpark for scalable data processing.
* Matplotlib and Seaborn for visualizations.

##  Conclusion
This project provides insights into what factors influence app popularity and success on the Google Play Store. Future work may involve incorporating more advanced machine learning models to predict app performance based on these attributes.
