# Vaccine-Prediction

## Business Case:-

To Create a predictive model for studying the future trends of vaccine for any particular diseases and to prepare a complete data analysis report on the given data.

## Domain Analysis:-

Vaccines provide immunization for individuals and a well-immunized community can further reduce the spread of diseases through "herd immunity".

In this dataset, we will look at vaccination, a vital public health measure that is used to fight infectious diseases.

Beginning in spring 2009, a pandemic caused by the H1N1 influenza virus, colloquially named "swine flu," swept across the world..

A vaccine for the H1N1 flu virus became publicly available in October 2009.

The goal is to predict how likely individuals are to receive their H1N1 and seasonal flu vaccines.

Specifically, we will be creating a predictive model for studying the future trends of vaccine for any particular diseases.

## Model Comparison Report:-

A model comparison report helps us to see whether which model performs the best.

By analyzing the various factors and how each model weighs, we gain a deeper understanding of decision-making processes, ultimately allowing us to make more strategic choices.

Based on our model comparison, Support Vector Machine appears to be the most promising model.

It achieved an accuracy of 100% and a precision of 100% and a recall score of 100% indicating strong overall performance.

## Challenges Faced:-

1. Importing the Data:

Since the raw excel file are segregated separately into labels and features, we founded it difficult to read and analyse the file. Ultimately, we found it difficult to concate the file.
2. Data Preprocessing:

Outlier Detection: Choosing the Right Technique is challenging one and there are Different methods (z-scores, IQR, isolation forests) have varying sensitivities. Selecting the most appropriate one depends on the data distribution so we selected IQR method to handle the outliers.

Computational Resources: Training and testing the models on a large dataset requires powerful computing resources and optimization techniques. So we used Data splitting and employed Robust scaler for scaling the data.

3. Model Training and Evaluation:

Model Selection and Interpretation: Choosing the best model and understanding its predictions can be challenging With various algorithms available, selecting the most suitable one requires careful consideration.

## Conclusion:-

After the complete analysis of the dataset, we arrive at the conclusion that Support Vector Machine is the best suitable output model that gives cent percent accuracy score, precision score and recall score.

This analysis helps in studying the future trends of vaccines for any particular diseases.
