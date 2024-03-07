# COVID-19 Age Group Analysis

This repository contains an R Markdown file that performs a comprehensive analysis of COVID-19 cases, focusing on the impact of age on the outcomes of the disease. The analysis includes data visualization, hypothesis testing, regression analysis, and model validation.

## Repository Contents

- `COVID-19 Age Group Analysis.Rmd`: This R Markdown file contains the code for the analysis. It includes data cleaning, visualization, hypothesis testing, regression analysis, and model validation.

- `COVID19_cases.csv`: This CSV file contains the data used in the analysis. It includes information about confirmed COVID-19 cases, such as age group and outcome (fatal or resolved).

- `COVID-19 Age Group Analysis.pdf`: This PDF file is the knitted output of the R Markdown file. It includes both the code and the results of the analysis, including tables and plots.

## Analysis Overview

The analysis is divided into several sections:

1. **Data Cleaning**: The data is loaded from the CSV file and cleaned to remove any missing or irrelevant values.

2. **Data Visualization**: Histograms and bar plots are created to visualize the distribution of cases and outcomes by age group.

3. **Hypothesis Testing**: Proportion tests are conducted to compare the proportions of fatal cases between different age groups.

4. **Bootstrap Proportion Test**: Bootstrap proportion tests are conducted to compare the observed sample proportion of fatal cases in different age groups to hypothesized values.

5. **Regression Analysis**: A logistic regression model is fitted to predict the outcome (fatal or not) based on the age group.

6. **Model Validation**: K-fold cross-validation is conducted to evaluate the performance of the logistic regression model.

The results of the analysis provide strong evidence that the risk of dying from COVID-19 increases with age.

## How to Run the Analysis

To run the analysis, you will need R and RStudio installed on your computer. You will also need to install the necessary R packages, which are listed at the beginning of the R Markdown file.

Once you have everything set up, you can run the analysis by opening the `COVID-19 Age Group Analysis.Rmd` file in RStudio and clicking the "Knit" button. This will run the code and generate the `COVID-19 Age Group Analysis.pdf` file.
