# Data analytics approach

For the second module I drafted a short deck for Sprocket Central on how I would decide which of the 1,000 new customers to target. The deck was built on the programme's PowerPoint template, which is marked for virtual internship use only, so it is not included. Below is the content of my slides, lightly copy-edited.

## Agenda

1. Introduction
2. Data exploration
3. Model development
4. Interpretation

## Introduction

Generating data-driven marketing products for new customers:

- Provide a convenient shopping experience for our customers.
- Offer products that are right on the spot.
- Make recommendations based on each customer's preferences.

## Data exploration

- Most of the data is clean, but some attributes need to be clarified with the client.
- Understand the distribution and skewness of the data.
- Standardise and transform the data before the model is deployed.
- Bring in external data to add more attributes, for example:
  - population data for the given states and suburbs
  - GDP and CPI indices
  - geographic data

## Model development

Recommendation system. Using the given data sets combined with external data, build a recommender based on each customer's personal information, requirements and preferences. The system should automatically suggest a range of suitable products for each customer.

## Interpretation

Use MAP@K and MAR@K as evaluation metrics to measure performance. Using more than one metric shows whether the recommendations are useful as well as relevant (Longo, 2018).

## References

- Australian Bureau of Statistics, <https://www.abs.gov.au/>
- Longo, C. (2018). Evaluation metrics for recommender systems. Towards Data Science. <https://towardsdatascience.com/evaluation-metrics-for-recommender-systems-df56c6611093>
