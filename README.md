# Data-Processing-at-Scale-Arizona-Nightlife-Analysis

This repository contains code, documentation, and reports for analyzing Yelp’s dataset to extract actionable insights on Arizona's Nightlife businesses. The project is designed to showcase the development of a scalable, distributed data pipeline and the use of advanced Spark SQL queries for both business-level and user-level analysis.

## Table of Contents
- [Project Overview](#project-overview)
- [Project Objectives](#project-objectives)
- [Prerequisites](#prerequisites)
- [Dataset Preparation](#dataset-preparation)
- [Running the Analysis](#running-the-analysis)
- [Results & Reports](#results--reports)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Project Overview
The project leverages Hadoop and Apache Spark (via PySpark) on an Ubuntu environment to process large-scale Yelp data. It transforms raw JSON data into optimized Parquet files for efficient distributed querying and analysis. The analysis is divided into two main components:
- **Business-Level Analysis:** Focused on extracting insights such as top-rated businesses, best-performing cities, and peak customer activity.
- **User-Level Analysis:** Focused on understanding user behavior, identifying influential reviewers, and analyzing seasonal trends in review activity.

## Project Objectives
The primary goals of this project are:
- **Scalability & Efficiency:** Develop a distributed data pipeline using Hadoop and Spark to process terabytes of Yelp data.
- **Data Transformation:** Convert raw JSON data into Parquet format to enable fast, efficient querying.
- **Business Insights:** Execute advanced Spark SQL queries to identify top-rated Arizona Nightlife businesses, evaluate city-level performance, and determine peak check-in patterns.
- **User Engagement Analysis:** Analyze user data to identify influential reviewers, understand elite user participation, and capture seasonal trends.
- **Actionable Recommendations:** Provide data-driven insights that can support strategic decisions in the Nightlife industry.

## Prerequisites
- **Operating System:** Ubuntu 22.04 LTS (or similar Linux environment, optionally via a Virtual Machine)
- **Java Development Kit (JDK):** Required for running Hadoop and Spark.
- **Apache Hadoop & Apache Spark:** Properly installed and configured.
- **Python 3.x:** With libraries specified in `requirements.txt`.
- **Jupyter Notebook:** For interactive development and running the notebooks.

## Dataset Preparation
Yelp Dataset:
- Download the dataset from the Yelp Open Dataset page : https://www.yelp.com/dataset

Filtering & Transformation:
- The project filters the dataset to include Arizona Nightlife businesses and converts the data from JSON to Parquet format for efficient analysis using Spark.

## Running the Analysis

### Business-Level Analysis
- **Transform & Query:**  
  Open `Business_Level_Analysis.ipynb` in Jupyter Notebook and execute the cells to transform raw Yelp JSON data into optimized Parquet files. Leverage advanced Spark SQL queries to extract critical insights on top-rated businesses, dynamic city performance, and customer check-in trends.
- **Visualization & Insights:**  
  The notebook generates intuitive visualizations that reveal market dynamics and customer engagement metrics, providing a strategic overview of Arizona’s premier Nightlife establishments.

### User-Level Analysis
- **Deep Dive into User Behavior:**  
  Open `User_Level_Analysis.ipynb` in Jupyter Notebook and run the cells to perform a comprehensive analysis of user review data. This analysis uncovers influential reviewers, elite user participation, and seasonal trends that shape consumer behavior.
- **Actionable Intelligence:**  
  The notebook applies sophisticated aggregation techniques and statistical analysis to deliver granular insights into user engagement and geographic distribution, empowering data-driven business strategies.

## Results & Reports
- **Business Analysis Report:**  
  A comprehensive report detailing key performance indicators, including top-rated establishments, city-level trends, and peak check-in periods. This report offers actionable insights for market analysis and strategic planning.  
  [View Business Analysis Report]([docs/Business_Analysis_Report])
- **User Analysis Report:**  
  An in-depth report highlighting user engagement patterns, influential reviewers, and seasonal activity trends. This document serves as a robust resource for understanding consumer behavior and guiding strategic decisions.  
  [View User Analysis Report](docs/User_Analysis_Report)
