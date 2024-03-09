# Starbucks Capstone Project

### (Link to Blog - Medium)[https://medium.com/@raghuvarankula/unlocking-the-brew-to-success-a-data-driven-dive-into-starbucks-app-offer-optimization-5b55186b94fc]

## Introduction
This repository contains the analysis for the Starbucks Capstone Challenge, part of the Data Science Nanodegree Program by Udacity. The project explores customer behavior on the Starbucks rewards mobile app to determine which demographic groups respond best to which type of offer (discount, BOGO, or informational).

## Libraries Used
- Pandas
- Numpy
- Matplotlib
- json
- datetime
- Seaborn
- Scikit-learn
- imblearn

## Project Motivation
This project aims to leverage the data provided by Starbucks, simulating customer transactions and interactions with offers sent through the mobile app. The goal is to understand the effectiveness of different promotional offers across various customer demographics, thereby enabling Starbucks to tailor their marketing strategies more efficiently.

## Files in the Repository
 - **Starbucks_Capstone_notebook.ipynb**: The Jupyter Notebook containing all the analysis, from data preprocessing to model evaluation and insights.
 - **README.md**: This file, providing an overview of the project and repository.
 - **pic1.png, pic2.png**: These images are used in Jupyter notebook for explaining the notebook terminal update process.

## Analysis Summary
The analysis involved several key steps:

1. **Data Exploration and Visualization**: Understanding the distribution of customer demographics and offer types.
2. **Data Preprocessing**: Cleaning the data and preparing it for modeling, including encoding categorical variables and handling missing values.
3. **Model Building**: Applying machine learning algorithms to predict customer response to offers.
4. **Model Evaluation**: Assessing model performance using accuracy and F1 score metrics.

## Key Findings:
Here are some key inferences drawn from the analysis:

1. **Age Distribution**:
 - The most active age group for all offers is between 55-60 years for females. For males, this shifts slightly higher for BOGO and Informational offers, where the 60-65 age group is most active.

2. **Income Bracket**:
 - The income bracket most actively participating in BOGO and Discount offers is 70-75 thousand for both genders, suggesting these offers might be more appealing to a higher income segment.
 - For Informational offers, the trend changes, with the most active income bracket being 50-55 thousand for the Generic group, 65-70 thousand for females, and 60-65 thousand for males, indicating that these offers might be targeting or more appealing to a lower to mid-income range.

3. **Reward Points**:
 - A significant number of reward points (539,505) were distributed by BOGO offers, with nearly half the reward points (201,188) distributed by Discount offers.

4. **Customer Interactions**:
 - In 2017, there were 24,316 customer interactions for BOGO offers, with discount offers customers engaging less (1,258) compared to BOGO. The trend is similar for Discount offers but not applicable for Informational offers.
 - Informational offers had significantly fewer interactions (8,689) than the other types, suggesting that customers may be less engaged with informational promotions.

5. **Other Gender**:
 - A minor segment is recorded under "other gender" with 914 for BOGO, 920 for Discount, and 356 for Informational offers, indicating participation but on a much smaller scale compared to the main categories.

6. **Offer Popularity (by rank and offer ID)**:
 - The top BOGO offer for both genders is "9b98b8c7a33c4b65b9aebfe6a799e6d9", while the top Discount offer is "fafdcd668e3743c1bb461111dcafc2a4".
 - The second most popular offer changes between BOGO and Discount, with "f19421c1d4aa40978ebb69ca19b0e20d" for BOGO and "2298d6c36e964ae4a3e7e9706d1fb8c2" for Discount.
 - Informational offers have two ranks listed, with "5a8bc65990b245e5a138643cd4eb9837" being the most completed Informational offer ID for both genders.

7. **Gender Differences**:
 - Males seem to have a slightly higher completion rate for offers across all categories, with the gap being more pronounced for Informational offers.

These inferences can help tailor marketing strategies, indicating potential areas to target specific demographics and suggesting that personalization by age, income, and gender could improve engagement and conversion rates for these promotional offers.


 - Model performance indicated that demographic features significantly influence the effectiveness of offers.
 - Suggestions for targeted marketing strategies were developed based on the insights gained from the analysis.

## Acknowledgements
 - Udacity for providing the framework and data for this capstone project.
 - Starbucks for the dataset simulating customer behavior on the rewards mobile app.
