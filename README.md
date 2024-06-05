# Keboola Jupyter Notebooks Guide

This repository contains a collection of Jupyter Notebooks designed to serve as guides for users of the Keboola platform. These notebooks provide step-by-step instructions and examples to help users efficiently utilize various features and functionalities available within Keboola.

## Notebooks Included

### Getting Started
**Introduction to Python Workspace**:
   - Introduction to using the Keboola workspace for development and analytical purposes.
   - Instructions on accessing data using Table Input Mapping and File Input Mapping.
   - Examples of loading input data into a DataFrame and displaying it.

**Working with Snowpark in Snowpark Python Workspace**:
   - Introduction to using the Snowpark library within the Snowpark Python Workspace.
   - Instructions on setting up Snowpark, performing data transformations, and saving results directly to Snowflake tables.

**Using MLFlow in Keboola Python Workspaces**:
   - Introduction to using MLFlow for managing machine learning experiments within Keboola Python Workspaces.
   - Instructions on setting up experiments, starting and ending runs, logging parameters and metrics, and registering models.
   - Demonstrates how to log an `input_example` and view results in the MLFlow UI.


### Advanced Analytics and Machine Learning
**Data Cleaning and Transformation**:
   - Practical examples of data cleaning and transformation tasks using Pandas and NumPy.
   - Detailed steps on handling missing values, removing duplicates, correcting data types, and creating new features.
   - Instructions on saving cleaned and transformed data back to Keboola Storage.

**Data Exploration and Profiling**:
   - **Introduction**: An overview of the notebook's purpose, emphasizing ease of data exploration and profiling.
   - **Install Required Packages**: Steps to install necessary libraries like ydata-profiling for generating data profiles.
   - **Import Libraries**: Importing essential libraries for data analysis, visualization, and interaction.
   - **Dataset Selection**: Instructions to list and select datasets using the Keboola Common Interface.
   - **Load Dataset**: Loading the selected dataset into a pandas DataFrame and generating a profile report.
   - **Generate Profile Report**: Creating a comprehensive HTML report of the dataset, with a note on handling large datasets.
   - **Remove Redundant Columns**: Identifying and dropping columns with only unique values and those that are not useful for binary classification models.
   - **Solve Duplicates**: Identifying and handling duplicate rows in the dataset.
   - **Encoding of Categorical Variables**: Detailed steps for one-hot and label encoding of categorical variables.
   - **Handle Missing Values**: Identifying and managing missing values using various strategies such as dropping or replacing missing data.
   - **Basic Dataset Details**: Checking and displaying basic descriptive statistics of the dataset.
   - **Anomaly Detection**: Performing skewness and kurtosis analysis for numeric variables, and identifying multivariate outliers using standard deviation and KNN methods.
   - **Explore Outliers**: Investigating rows identified as outliers to understand their impact on the dataset.

**Association Rules**:
   - **Introduction** - Association rule mining is a powerful technique for discovering interesting relationships, patterns, and associations among a set of items in large datasets. It is widely used in market basket analysis, recommendation systems, and various fields where understanding the co-occurrence of items is valuable.

   - **What is mlxtend?** - `mlxtend` (Machine Learning Extensions) is a Python library that provides a range of tools and extensions for data science and machine learning. Among its many features, `mlxtend` includes robust implementations for frequent itemset generation and association rule mining.

   - **Key Concepts in Association Rule Mining:**
        - **Frequent Itemsets**: Sets of items that appear together in a dataset with a frequency above a specified threshold.
        - **Support**: The proportion of transactions in the dataset that contain a particular itemset.
        - **Confidence**: The likelihood that a rule's consequent is present in transactions that contain the rule's antecedent.
        - **Lift**: The ratio of the observed support to the expected support if the items were independent.

   - **Why Use Association Rule Mining?**
        - **Market Basket Analysis**: Understand which products are often bought together to optimize product placement, promotions, and inventory management.
        - **Recommendation Systems**: Suggest items to users based on their past behaviors and the behaviors of similar users.
        - **Anomaly Detection**: Identify unusual patterns or associations that could indicate errors, fraud, or other significant events.

**Causal Inference Analysis**:
   - **Introduction** - Causal inference is a crucial aspect of data analysis that goes beyond correlation to understand the cause-and-effect relationships between variables. Unlike traditional statistical methods, causal inference aims to answer questions about what happens to one variable when another variable is manipulated.

   - **What is DoWhy?** - `DoWhy` is a Python library that provides a principled approach to causal inference. It leverages a combination of state-of-the-art algorithms and established causal inference techniques to allow users to estimate causal effects from observational data.

   - **Key Features of DoWhy:
        - **Modeling Assumptions**: Explicitly state assumptions about the causal model using a graphical representation (causal graph).
        - **Identification**: Automatically identify if the causal effect can be estimated from the given data and assumptions.
        - **Estimation**: Use a variety of methods to estimate the causal effect, including regression, matching, instrumental variables, and more.
        - **Refutation**: Perform robustness checks to test the validity of the estimated causal effect.

   - **Why Causal Inference?** - Causal inference is essential for:
        - Understanding the true impact of interventions or treatments.
        - Making informed decisions based on the likely outcomes of different actions.
        - Going beyond simple associations to uncover the mechanisms behind observed data patterns.

   - **Objectives of This Notebook
        1. Setup and Installation

        2. Connecting to Snowflake using Snowpark

        3. Fetching Data and Loading it into a Pandas DataFrame

        4. Performing Causal Inference with DoWhy


### Keboola APIs and Components
**Working with Keboola APIs**:
   - Guide on performing basic operations with Keboola's API using the `requests` library and `kbcstorage` client.
   - Examples of listing buckets and tables, listing configurations, fetching configuration details, and creating or updating resources.


## How to Use These Notebooks

Each notebook is self-contained and provides detailed instructions and code examples. Users can follow along, modify the code as needed, and apply the concepts to their own projects within Keboola.

## Additional Resources

For more information on Keboola and its features, please refer to the [Keboola Documentation](https://help.keboola.com/).

