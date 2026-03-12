# Lisbon Attractions Reviews – Data Science for Marketing

## Project Overview

This project analyzes Tripadvisor reviews of Lisbon attractions to generate actionable insights for the Lisbon Tourism Authority (LTA). Using data science techniques and the CRISP-DM methodology, the project transforms unstructured visitor feedback into measurable indicators of visitor satisfaction, experience quality, and operational performance.

The objective is to identify the main drivers of satisfaction and dissatisfaction, detect operational issues such as crowding or waiting times, and support evidence-based marketing and tourism management decisions.

## Objectives

* Measure overall visitor satisfaction across attractions and categories.
* Identify the key drivers of positive and negative visitor experiences.
* Analyze visitor behavior and engagement patterns in reviews.
* Detect operational themes such as queues, staff experience, and pricing perception.
* Provide data-driven insights to support marketing and visitor experience strategies.

## Data

The analysis uses three datasets derived from Tripadvisor:

* **attraction_data_reviews.csv** – review-level information (ratings, text, reviewer data, dates)
* **attractions_data_metadata.csv** – attraction characteristics and performance indicators
* **attractions_list.csv** – list of attractions included in the study

The dataset contains variables related to:

* Visitor reviews and ratings
* Attraction metadata and rankings
* Visitor engagement (likes, contributions, replies)
* Temporal information about visits and reviews

## Methodology

The project follows the **CRISP-DM (Cross Industry Standard Process for Data Mining)** framework:

1. **Business Understanding** – Define business objectives and tourism performance indicators.
2. **Data Understanding** – Explore the structure, completeness, and patterns in the dataset.
3. **Data Preparation** – Clean and transform the data, engineer features, and handle inconsistencies.
4. **Modeling & Analysis** – Apply exploratory analysis, sentiment analysis, and behavioral metrics.
5. **Evaluation** – Validate insights and assess their business relevance.
6. **Deployment** – Provide insights and recommendations for tourism management and marketing strategy.

Key techniques include:

* Exploratory Data Analysis (EDA)
* Sentiment analysis on review text
* Feature engineering
* Visitor engagement metrics
* Adapted RFM (Recency, Frequency, Monetary) analysis
* Keyword-based topic detection

## Key Insights Explored

* Distribution and drivers of visitor satisfaction
* Seasonal patterns in tourism activity
* Operational issues such as waiting times or staff interactions
* Review engagement patterns and reputational impact
* Relative performance of attractions within categories

## Repository Structure

* DS4M_Project: Main project notebook
* GroupProject_Information: Project description
* Data: Project datasets
* README.md: Project documentation

## Tools and Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* NLTK
* Scikit-learn
* Langdetect
