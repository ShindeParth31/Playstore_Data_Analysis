# Google Play Store Data Analysis Project - README
 ## 
 Project Overview
 This project performs a complete exploratory data analysis (EDA) on a Google Play Store dataset,
 including:- Data cleaning and preprocessing- Category-wise exploration- Metrics analysis (Ratings, Installs, Size, Price)- Sentiment analysis using textual reviews- Interactive visualizations using Plotly
 It is designed to run fully on **Google Colab**, including support for uploading datasets as **ZIP files**.--
## 
 Dataset Description
 The dataset used contains the following columns:- **App** – App name- **Category** – Category of the app- **Rating** – Average user rating- **Reviews** – Number of reviews- **Review** – Textual user review (used for sentiment analysis)- **Size** – App size- **Installs** – Total installs- **Type** – Free or Paid- **Price** – Price of the app- **Content Rating** – Age suitability- **Genres** – Genre of the app- **Last Updated** – Last updated date- **Current Ver** – Version number- **Android Ver** – Minimum required OS version
This dataset was custom-created to ensure **all important columns** are included without missing
 values.--
## 
 Steps Included in the Colab Notebook
 1. **Import Libraries**
 2. **Upload ZIP File**
 3. **Extract CSV Automatically**
 4. **Load Dataset into DataFrame**
 5. **Data Cleaning (Robust & Automated)**
 6. **Category Analysis**
 7. **Metrics Analysis**
 8. **Sentiment Analysis**
 9. **Interactive Visualizations**
 10. **Final Summary**--
## 
 Data Cleaning Features
 The notebook handles:- Missing columns- Missing values- Incorrect data types- Cleaning Installs, Size, Price columns- Converting dates- Filling NA values safely--
## 
 Visualizations
 The script includes:
- Bar charts- Histograms- Scatterplots- Bubble charts- Plotly interactive charts--
## 
 Sentiment Analysis
 Sentiment polarity is calculated using **TextBlob** on the *Review* column.--
## 
 How to Run This Project in Google Colab
 1. Open Google Colab
 2. Upload the `.zip` dataset using the provided code
 3. Run each step cell-by-cell
 4. Explore insights and graph
