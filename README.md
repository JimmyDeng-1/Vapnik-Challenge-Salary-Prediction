# Vapnik-Challenge-Salary-Prediction
A predictive modeling project using R to estimate university graduate salaries based on student and institutional data for the Rutgers Vapnik Challenge.
# Vapnik Challenge: Graduate Salary Prediction

## Project Overview
This project focuses on building a predictive model to estimate the starting salaries of university graduates. The goal is to minimize the Mean Squared Error (MSE) by analyzing various factors from both institutional (university) and individual (student) datasets.

## Objectives
* **Data Integration:** Merging and cleaning separate datasets containing university-specific information and student performance metrics.
* **Regression Analysis:** Implementing regression models to identify the strongest predictors of salary outcomes.
* **Error Diagnosis:** Utilizing Recursive Partitioning (`rpart`) to categorize error levels and identify specific areas where the model's predictions fail.
* **Model Optimization:** Refining features and model parameters to achieve a competitive MSE.

## Methodology
* **Language:** R
* **Core Libraries:** `rpart`, `ggplot2`, `dplyr`
* **Evaluation Metric:** Mean Squared Error (MSE)

## Key Challenges
The primary challenge of this project was managing high-variance data and understanding why certain segments (e.g., specific majors or school tiers) resulted in higher prediction errors. By using decision trees for error analysis, I was able to pinpoint and address these "unacceptable" error categories.

## Competition Links
The project was part of a competitive challenge hosted on Kaggle:
[Link to Kaggle Competition] *(Replace this with your actual Kaggle profile or competition link)*

## Repository Structure
* `/data`: Dataset files (if allowed by competition rules).
* `/scripts`: R script files used for data processing and modeling.
* `submission.csv`: Final output for the challenge.
