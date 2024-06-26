# Keboola Jupyter Notebooks Guide

This repository contains Jupyter Notebooks designed to guide users of the Keboola platform. These notebooks provide step-by-step instructions and examples for efficiently utilizing various features and functionalities within Keboola.

## Notebooks Included

---
### Getting Started
**Introduction to Python Workspace**:
   - Using the Keboola workspace for development and analytics.
   - Accessing data via Table Input Mapping and File Input Mapping.
   - Loading input data into a DataFrame.

**Working with Snowpark in Snowpark Python Workspace**:
   - Using the Snowpark library within the Snowpark Python Workspace.
   - Setting up Snowpark, performing data transformations, and saving results to Snowflake tables.

**Using MLFlow in Keboola Python Workspaces**:
   - Managing machine learning experiments with MLFlow.
   - Setting up experiments, logging parameters and metrics, and registering models.

---
### Advanced Analytics and Machine Learning
**Data Cleaning and Transformation**:
   - Data cleaning and transformation tasks using Pandas and NumPy.
   - Handling missing values, removing duplicates, correcting data types, and creating new features.
   - Saving cleaned data back to Keboola Storage.

**Data Exploration and Profiling**:
   - Steps for data exploration and profiling.
   - Generating profile reports, removing redundant columns, handling duplicates, encoding categorical variables, and handling missing values.

**Association Rules**:
   - Introduction to association rule mining and its applications.
   - Using `mlxtend` for frequent itemset generation and association rule mining.

**Causal Inference Analysis**:
   - Understanding causal relationships between variables.
   - Using `DoWhy` for causal inference.

**Data Preparation for ML**:
   - Importing packages, loading datasets, exploring data, and cleaning data.
   - Removing redundant columns, solving duplicates, handling missing values, encoding categorical variables, feature scaling, dimensionality reduction, and dataset splitting.
   - Exporting the transformed dataset.
   
**AutoML with H2O**:
   - Load train and test datasets, select the target variable.
   - Calculate GINI on train and test datasets.
   - Analyze feature importance using XGBoost and L1 regularized logistic regression, Handle highly correlated features based on user-defined threshold.
   - Select important features based on analysis, Train models using H2O AutoML and display the leaderboard.

**Using MLFlow Model in Keboola Transformation**:
   - **Initialize MLFlow and Set Experiment**: Optionally log the usage of the deployed model into an MLFlow experiment. Users can enter or select an experiment name.
   - **Load the Dataset**: Load the input dataset using the Keboola Common Interface. **Specify the Model Endpoint URL**
   - **Invoke the Deployed Model**: Send the processed dataframe to the model endpoint and receive predictions.
   - **Log Model Monitoring Metrics**: Optionally log descriptive statistics of the dataframe for model monitoring in MLFlow.


---
### Keboola APIs and Components
**Working with Keboola APIs**:
   - Performing basic operations with Keboola's API.
   - Listing buckets and tables, fetching configuration details, and creating or updating resources.

## How to Use These Notebooks

Each notebook is self-contained with detailed instructions and code examples. Users can follow along, modify the code, and apply the concepts to their own projects within Keboola.

## Additional Resources

For more information on Keboola and its features, please refer to the [Keboola Documentation](https://help.keboola.com/).
