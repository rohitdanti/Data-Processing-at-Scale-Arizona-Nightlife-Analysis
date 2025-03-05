# Data-Processing-at-Scale-Arizona-Nightlife-Analysis

This repository contains code, documentation, and reports for analyzing Yelp’s dataset to extract actionable insights on Arizona's Nightlife businesses. The project is designed to showcase the development of a scalable, distributed data pipeline and the use of advanced Spark SQL queries for both business-level and user-level analysis.

## Table of Contents
- [Project Overview](#project-overview)
- [Project Objectives](#project-objectives)
- [Repository Structure](#repository-structure)
- [Prerequisites](#prerequisites)
- [Installation & Setup](#installation--setup)
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
