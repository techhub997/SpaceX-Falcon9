# **SpaceX Falcon 9: Predictive Landing & Data Pipeline**

## **Project Overview**

This project aims to predict the success of SpaceX Falcon 9 first-stage landings—a key factor in determining launch costs and commercial viability. By leveraging the entire Data Science lifecycle, I built a predictive model to determine if a booster will land successfully, potentially saving millions in launch expenses.

## **📁 Key Components & Files**

The repository is structured to reflect the end-to-end workflow:

**Data Acquisition**: * jupyter-labs-spacex-data-collection-api.ipynb: Extracting launch data via the SpaceX REST API.

**jupyter-labs-webscraping.ipynb**: Scraping Wikipedia data to supplement historical launch records.

**Data Engineering & EDA**: * labs-jupyter-spacex-Data wrangling.ipynb: Cleaning, handling nulls, and feature engineering.

**jupyter-labs-eda-sql-coursera_sqllite.ipynb**: Using SQL queries to uncover launch site patterns and payload trends.


**edadataviz.ipynb**: Visualizing data distributions and identifying landing success drivers.

**Geospatial & Interactive Analysis**: * lab_jupyter_launch_site_location.ipynb: Mapping launch sites and success rates using Folium.

**spacex-dash-app.py**: An interactive Plotly Dash dashboard for real-time data exploration and site-specific filtering.

**Machine Learning:** * SpaceX_Machine_Learning_Prediction_Part_5.ipynb: Training and comparing multiple classification models (Logistic Regression, SVM, Decision Tree, KNN) to find the most accurate predictor.

## **📊 Business Insights**
**Launch Site Optimization**: Identified specific launch pads with higher historical success rates, correlating with payload weight and orbit types.

**Predictive Accuracy**: Achieved a peak accuracy of 83.33% using Logistic Regression, providing a high-confidence tool for launch cost estimation.

**Interactive Visuals**: Built a geospatial dashboard that allows stakeholders to visualize the proximity of launch sites to coastlines and highways—critical factors in landing logistics.

## **🛠 Tech Stack**

**Language**: Python

**Libraries**: Pandas, NumPy, Scikit-learn, Folium, Plotly Dash, Beautiful Soup (Web Scraping).

**Databases**: SQL (SQLite)

**API**: SpaceX REST API

## **🏆 Accomplishments**

Completed as part of the IBM Data Science Professional Certificate.

Demonstrated proficiency in automating data pipelines and translating raw sensor/launch data into actionable business intelligence.

