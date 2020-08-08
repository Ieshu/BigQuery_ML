# BigQuery_ML

This tutorial introduces data analysts to BigQuery ML. BigQuery ML enables users to create and execute machine learning models in BigQuery using SQL queries. The goal is to democratize machine learning by enabling SQL practitioners to build models using their existing tools and to increase development speed by eliminating the need for data movement.

In this code, we will use the natality sample table to create a model that predicts the birth weight of a child based on the baby's gender, the length of the pregnancy, and demographic information about the mother. The natality sample table contains information about every birth in the United States over a 40 year period.

In this code, you use:

BigQuery ML to create a linear regression model using the CREATE MODEL statement

The ML.EVALUATE function to evaluate the ML model

The ML.PREDICT function to make predictions using the ML model
