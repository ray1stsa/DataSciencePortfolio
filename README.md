
# Game Success Prediction and Analysis

## Overview
This project uses **machine learning** (XGBoost) to predict video game **Meta Scores** and analyze the factors that drive a game's success, including **platform**, **release date**, and **user reviews**. Our goal is to help developers and publishers make data-driven decisions to improve game performance.

## Motivation
The project was motivated by the need to understand what factors most contribute to a game’s critical reception. By leveraging AI and data analysis, stakeholders can make better-informed decisions regarding game development, release timing, and marketing strategies.

## Libraries Used
- **pandas**: For data manipulation and cleaning.
- **matplotlib**: For data visualization and plotting results.
- **seaborn**: For advanced data visualizations.
- **XGBoost**: For regression and classification tasks to predict game Meta Scores.
- **scikit-learn**: For splitting the data into training and test sets, and for evaluation metrics.

## Files in the Repository
- **README.md**: Project description and overview (this file).
- **game_meta_score_analysis.ipynb**: Jupyter notebook containing the full analysis and implementation of the machine learning models (regression, classification).
- **data/**: Folder containing the dataset used in the project.
  - **all_games.csv**: The dataset of games with platform, release date, Meta Score, and user reviews.

## Summary of Results
- **Platform Analysis**: High-performance platforms like **PlayStation** and **Xbox** do not always guarantee higher Meta Scores. Classic platforms like **Nintendo 64** showed higher average scores, likely due to fewer iconic game releases.
- **Release Timing**: Games released in **Q3 (July to September)** tend to perform better in terms of Meta Scores compared to the oversaturated **Q4 (holiday season)**.
- **Meta Score Prediction**: We implemented an **XGBoost Regressor** to predict Meta Scores, achieving an R-squared score of 0.41.

## Acknowledgements
We would like to thank the open-source libraries and tools (pandas, XGBoost, scikit-learn) that made this project possible. Special thanks to kaggle  that provided the data used for the analysis.

## Links 
URL of the GitHub repo : https://github.com/ray1stsa/DataSciencePortfolio/tree/main

Medium Post : https://medium.com/@rayanalshehri81/what-drives-game-success-2ba2792dd5d9
