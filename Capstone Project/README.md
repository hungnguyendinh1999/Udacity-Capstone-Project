# Book Review Data Pipeline
### Data Engineering Capstone Project

Imagine that your company is collecting book reviews from users for further data analysis. Currently, the main goal is to have some Star Schema for the Data Analysts to create dashboards to present their findings on current book trends and common user ratings.

This project is done

Data Source: 
[Book Rating Dataset from Kaggle](https://www.kaggle.com/datasets/ruchi798/bookcrossing-dataset)

## Content
1. [Project Structure](#project-structure)
2. [Pipeline Design](#pipeline-design)
3. [How to Run](#how-to-run)
4. [Schema Design](#schema-design)

# Project Structure
```
Capstone Project
|____data                                   # table setup script
|    |____Book reviews                      # Source data
|    |____Book Data with Categor...         # Source data
|    |____model                             # Output - Final tables store
|____images                                 # images for document purposes
|____Book Review Data Pipeline.ipynb        # Main Project workspace
|____Data Dictionary.xlsx                   # Main Project workspace
|____dbdiagram.io.txt                       # Script to generate Schema on dbdiagram.io website
```


# Pipeline Design
The pipeline is implemented locally in [the Jupyter notebook](Book Review Data Pipeline.ipynb). Please take a look there.

# Schema Design
![Data Model](images/data-model.png)