# 🚀 IBM Data Science Capstone Project – Predicting Falcon 9 First Stage Landing Success

This repository contains my final capstone project for the **IBM Data Science Professional Certificate**, where I applied data science techniques to predict the success of **SpaceX Falcon 9 first-stage landings**. The goal was to analyze historical launch data and build machine learning models that can help estimate the probability of a successful landing.

---

## 📘 Project Overview

SpaceX has revolutionized space travel by reusing rocket components—particularly the Falcon 9 first stage. Predicting whether a launch will result in a successful landing has major cost implications. This project uses **API data, web-scraping, visualization, and machine learning** to explore and model landing outcomes.

---

## 🎯 Objectives

- Collect and wrangle launch data from SpaceX API and Wikipedia  
- Perform exploratory data analysis using **visuals** and **SQL**  
- Build **interactive dashboards** and **maps** with Plotly Dash and Folium  
- Train and evaluate **classification models** to predict landing outcomes  
- Determine the **most influential factors** behind successful landings

---

## 🧪 Methodology

### 🔹 Data Collection
- **SpaceX API** for real-time launch metadata (e.g., payload, orbit, launch site, etc.)
- **Web scraping** from Wikipedia to enrich and validate launch records

### 🔹 Data Wrangling
- Cleaning and merging data from multiple sources
- Encoding mission outcomes into binary classification labels (success = 1, failure = 0)

### 🔹 Exploratory Data Analysis (EDA)
- Visualizing trends using Matplotlib and Seaborn
- SQL-based querying to uncover deeper insights (e.g., top payloads, site success rates)

### 🔹 Interactive Visualizations
- **Folium** maps for geospatial analysis of launch sites  
- **Plotly Dash** dashboard for real-time, user-driven exploration

### 🔹 Machine Learning
- Models: **Logistic Regression**, **Decision Trees**, **Random Forests**, **SVM**  
- Evaluation via accuracy score, confusion matrix, and cross-validation  
- Best model: **Decision Tree**, with ~87.5% training accuracy and ~83.3% test accuracy

---

## 📈 Key Insights

- Launch success rates significantly improved from **2013 to 2020** (by ~80%)
- **KSC LC-39A** is the most successful launch site overall  
- Orbits like **SSO, GEO, and HEO** had higher landing success rates than others  
- Payload mass has a weak direct correlation to success, but **certain payload-orbit pairs** perform better  
- **Flight experience matters**—more flight numbers = higher success rates

---

## 🧰 Tools & Technologies

- **Python**, **Pandas**, **NumPy**
- **SQL** for advanced querying  
- **Matplotlib**, **Seaborn** for static visualizations  
- **Folium**, **Plotly Dash** for interactive visualizations  
- **Scikit-learn** for classification modeling  
- **Jupyter Notebook**

---

## 📄 Final Report

📥 [View Full Report (PDF)](https://github.com/ZeroZulu/IBM-Data-Science-Capstone/blob/main/IBM%20Data%20Science%20Capstone%20Project.pdf)

Includes methodology, code logic, visual insights, and model evaluation.

---

## 🙌 Acknowledgements

This project was completed as part of the **IBM Data Science Professional Certificate on Coursera**. Special thanks to the instructors, IBM, and the open data community.

---
