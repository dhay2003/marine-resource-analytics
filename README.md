# Marine Resource Analytics

## Overview

This project analyzes over 4,000 abalone records to explore relationships between environmental conditions, physical characteristics, and biological maturity

Using Python Machine Learning and data visualization techniques, the analysis explores relationships between physical measurements, water conditions, and ring count, a commonly used indicator of abalone age. 
## Objectives
- Analyze regional differences in abalone populations
- Investigate relationships between environmental conditions and maturity
- Identify biological characteristics associated with growth
- Develop interactive visualizations to communinicate findings
- Build a portfolio-ready analytics soultion using industry-standard tools

## Dataset

The dataset contains: 
- Biological measurements
- Weight metrics
- Water temperature
- Geographic collection regions
- Ring count (age indicator)


## Tool Used

 - Python
 - Pandas
 - Scikit-Learn
 - Matplotlib
 - Seaborn
 - Git
 - GitHub

## Research Questions

 1. Which biological measurements are most strongly associated with maturity?
 2. Does water temperature influence ring count?
 3. How do maturity levels vary across regions?
 4. Can machine learning predict ring count using physical measurements?

## Exploratory Data Analysis
The dataset was evaluated for completeness, distribution patterns, and relationships between biological and environmental variables. 

### Key Findings

#### Finding 1

Shell weight was the strongest predictor of maturity with a correlation of 0.63 and accounted for over 50% of Random Forest feature importance. 

#### Finding 2

Water temperature demonstratd almsot no relationship with maturity (correlation = -0.022).

#### Finding 3 

Mid-Atlantic populations exhibited the higest average maturity levels among sampled regions. 

#### Finding 4 

Biological characteristics explained maturity differences more effectively than environmental temperature. 

## Machine Learning Results
Random Forest Regression
R^2 Score: 0.53
The model successfully captured meaningful relationships between physical charac teristics adn ring count.

## Visualizations

### Correlation Heatmap
correlation_heatmap
### Shell Weight vs Rings
visualizations/correlation_heatmap.png
### Feature Importance
visualizations/feature_importance.png
### Actual vs Predicted
visualizations/actual_vs_predicted.png

