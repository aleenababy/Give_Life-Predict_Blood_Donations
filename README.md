# **Blood Donation Prediction**

## Overview

Blood transfusions are critical for saving lives, from replacing lost blood during major surgery or serious injuries to treating various illnesses and blood disorders. Ensuring a sufficient blood supply is a significant challenge for health professionals. According to WebMD, "about 5 million Americans need a blood transfusion every year."

Our dataset comes from a mobile blood donation vehicle in Taiwan. The Blood Transfusion Service Center drives to different universities to collect blood as part of a blood drive. This project aims to predict whether or not a donor will give blood the next time the vehicle comes to campus.

## Dataset

The dataset is located in datasets/transfusion.data and is structured according to the RFMTC marketing model, a variation of the RFM (Recency, Frequency, Monetary) model.

### Data Structure
- Recency: Number of months since the last donation.
- Frequency: Total number of donations.
- Monetary: Total blood donated in c.c.
- Time: Number of months since the first donation.
- Target: Whether the donor donated blood in March 2007 (1: Yes, 0: No).
  
## Project Goals

- Predictive Modeling: Develop a model to predict whether a donor will donate blood during the next visit.
- Data Exploration: Understand the dataset and its features.
- Model Evaluation: Assess the performance of various machine learning models.

## Instructions

- Data Inspection: Begin by inspecting the dataset to understand its structure and contents.
- Pre-processing: Handle any missing values, normalize features, and prepare the data for modeling.
- Model Development: Use various machine learning algorithms to build predictive models.
- Model Evaluation: Evaluate the models using appropriate metrics and select the best-performing model.
- Prediction: Use the selected model to make predictions on new data.

## How to Use

- Clone the Repository: Clone this repository to your local machine.
- Run the Notebook: Open and run the provided Jupyter notebook to explore the data, build, and evaluate models.

## Repository Structure

- datasets/: Contains the transfusion.data file.
- notebooks/: Jupyter notebooks for data exploration, model building, and evaluation.

## References
- WebMD: Blood Transfusions
- UCI Machine Learning Repository: Blood Transfusion Service Center Data Set
