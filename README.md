Automobile Sales, Insurance, and Review Analysis

This repository contains code and documentation for analyzing automobile sales data, insurance claims data, and car reviews. The analysis aims to provide insights into various aspects of the automobile industry, including sales trends, customer sentiment, insurance claim patterns, and geographical distribution of incidents.

Dataset
The dataset used in this analysis comprises three main components:

Car Sales Data: Contains information about automobile sales, including company, model, engine specifications, transmission type, price, and more.

Insurance Claims Data: Includes details about insurance claims, such as policy information, incident type, severity, total claim amount, and fraud reported status.

Car Reviews Data: Consists of reviews written by customers about different car models, covering aspects like overall rating, sentiment, and specific feedback.

Data Pre-processing
Before conducting the analysis, the datasets undergo pre-processing steps, including:

Converting all text data to lowercase for consistency.
Merging the datasets using inner joins based on the composite key of "Company" and "Model" to combine sales, insurance, and review data.

Exploratory Data Analysis (EDA)

The EDA phase involves:
Calculating summary statistics to understand the dataset's characteristics.
Visualizing data distributions and relationships using boxplots, histograms, and bar plots.
Handling missing values and identifying potential outliers.
Analyzing demographic information, policy characteristics, and claim distributions.

Modeling

The modeling phase focuses on building a generalized linear model (GLM) to explore the relationship between various predictors and the total claim amount in insurance data. Predictors include demographic information, policy details, incident characteristics, and more.

Sentiment Analysis

Sentiment analysis is performed on the car review data to gauge the sentiment expressed in customer reviews for different car models. The sentiment scores provide insights into how customers perceive different models from various companies.

Word Cloud

A word cloud is generated to visualize the frequency of incident types recorded in insurance claims data. This visualization helps identify prevalent incident types within the dataset.

Geographical Data Analysis

Geographical plotting is conducted to visualize the locations of incidents recorded in the insurance claims data. By leveraging city and state information, incidents are pinpointed on a dynamic map, providing a comprehensive geographical representation.

Repository Structure

Code: Contains R scripts for data loading, pre-processing, exploratory analysis, modeling, sentiment analysis, word cloud generation, and geographical plotting.
Data: Includes the datasets used in the analysis.
Documentation: Consists of the README document providing an overview of the analysis, its objectives, methodologies, and findings.

Usage

To replicate the analysis, follow these steps:
Clone the repository to your local machine.
Install the required R packages listed in the documentation.
Run the R scripts in the "Code" directory in the specified order to execute the analysis.

Contributor-

Snigdha Chaudhuri
https://github.com/Snigdha0603
