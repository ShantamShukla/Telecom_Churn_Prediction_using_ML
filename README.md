# Telecom Churn Prediction

## Problem Statement
In the highly competitive telecom industry, the annual churn rate averages 15-25%. As customer acquisition costs increase, retaining high-profit customers becomes more important. To reduce churn, telecom companies need to predict which customers are at high risk of churn. In this project, customer-level data from a leading telecom firm will be analyzed to build predictive models that identify high-risk customers and the primary indicators of churn.

## Understanding and Defining Churn

In the telecom industry, two payment models exist: postpaid and prepaid. Postpaid customers usually inform the operator when switching services, while prepaid customers can simply stop using services without notice. To predict churn, it is critical to define churn carefully. This project is based on the Indian and Southeast Asian market and uses a usage-based definition of churn.

## High-value Churn

Approximately 80% of revenue in the Indian and Southeast Asian market comes from the top 20% of customers, known as high-value customers. Reducing churn among these customers will significantly reduce revenue loss. In this project, high-value customers will be defined based on specific metrics and only high-value customers will be included in churn prediction.

## Understanding the Business Objective and the Data

Customer-level information for four consecutive months is included in the dataset - June, July, August, and September. The goal is to predict churn in September using features from June, July, and August. Understanding customer behavior during churn is helpful for achieving this task.

## Dataset and Data Dictionary

The dataset and data dictionary for this project can be downloaded from the provided link. The data dictionary includes meanings for abbreviations such as loc (local), IC (incoming), OG (outgoing), and T2T (telecom).