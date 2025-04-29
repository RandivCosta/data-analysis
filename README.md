# Data Processing Pipeline

This document outlines the steps and components of the data processing pipeline.

## 1. Data Loading and Cleaning

This stage focuses on ingesting raw data and preparing it for analysis.

* **Libraries Used:** `pandas`, `numpy`
* **Key Processes:**
    * Standardized column names for consistency.
    * Converted categorical labels to numerical values where necessary.
    * Created derived metrics (e.g., mean columns) to capture relevant features.

## 2. Analysis Execution

This stage involves performing the core data analysis based on the cleaned data.

* **Libraries Used:** `statsmodels`, `scipy`, `scikit-learn`, `numpy`
* **Key Processes:**
    * Executed various analysis types using a modular Python script.
    * Analysis was performed separately for different data subsets (e.g., seawater and sand).
    * Utilized iterative methods (e.g., nested loops) for calculations requiring iteration through specific dimensions like sites and areas.
    * Implemented a systematic approach for storing results using Python dictionaries, providing a structured and readable output for subsequent steps.

## 3. Output Generation

This final stage handles the storage and visualization of the analysis results.

* **Libraries Used:** `matplotlib`, `seaborn`
* **Key Processes:**
    * Implemented a system to store structured results in `.csv` files.
    * Generated `.png` images for all data visualizations.
    * Statistical test results were provided as command line outputs for immediate, temporary review.
