# DS3001_TeamM_Project
# Hospital Mortality Analysis Case Study

This repository contains the data, code, and paper components for our group’s case study examining factors that influence risk-adjusted mortality rates across hospitals. Our goal was to investigate the relationship between hospital characteristics and mortality outcomes, and to compare several predictive modeling techniques.

---

## Project Overview

In this project, we analyzed hospital mortality data from 2016–2023, which we cleaned to just 2023 data and implemented multiple models including Linear Regression, Decision Trees, K-Nearest Neighbors (KNN), and a Neural Network to see which approaches most effectively predict mortality outcomes. We also documented our methodology, initial analyses, and final findings through several written components that accompany the code.

---

## Repository Structure

The repository is organized into three main folders to keep everything clean and easy to navigate.

### DATA
This folder contains all raw and cleaned datasets, along with documentation.
- `2016-2023-imi-results-long-view.csv` – Long-view IMI results dataset (2016–2023)  
- `hospital data cleaned.csv` – Cleaned dataset used for modeling
- `METADATA.md` - Documentation for the dataset
- `EDA 1.png` - A exploratory plot for the metadata, about Risk Adjusted Mortality Rate by Hospital Rating
- `EDA 2.png` - A exploratory plot for the metadata, about the Frequency of Medical Conditions
- `EDA 3.png` - A exploratory plot for the metadata, about the Risk Adjusted Mortality Rate by Condition


### SCRIPTS
All Jupyter notebooks related to modeling and analysis.

- `EDA.ipynb` – Exploratory data anaylsis for the dataset  
- `KNNresultsmilestone.ipynb` – KNN regression model and milestone results  
- `linearregression.ipynb` – Linear regression modeling and interpretation  
- `trees.ipynb` – Decision tree modeling  
- `neuralnetwork.ipynb` – Neural network experiments  

---

### PAPER COMPONENTS
All of our written documents that contributed to the final paper.

- `Final_Paper.pdf` – Our completed case study report (final paper) 
- `Pre-Analysis Plan.pdf` – Research design and methods outline (or methods)  
- `Data_Description.pdf` – Data documentation also referenced in the paper  
- `Preliminary Results.pdf` – Early results used to guide our model decisions  

---

## How to Access the Cleaned Data

If you want to quickly view or download the cleaned dataset used in our models:

1. Navigate to the DATA folder in this GitHub repository.  
2. Click on `hospital data cleaned.csv`.  
3. Select Download or Open Raw to view the file directly.  

This file contains the final processed variables used across all modeling notebooks.

---

## How to Clone the Repository

If you'd like to run the notebooks, use: 

! git clone https://github.com/hildj/DS3001_TeamM_Project
