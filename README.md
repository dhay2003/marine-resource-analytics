# Marine Resource Analytics

## Overview

This project analyzes over 4,000 abalone records to explore relationships between environmental conditions, physical characteristics, and biological maturity

Using SQL, Python, and Tableau, the project explores relationships between water temperature, geographic region, shell measurements, weight metrics, and abalone age indicators.

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
 - Tableau Public
 - Git
 - GitHub

## Research Questions

  1. Which water regions contain the oldest abalones?
  2. Is water temperature related to age?
  3. Which biological measurements best predict maturity?
  4. How do growth characterisitcs differ by gender?

## Key Findings

### Finding 1

Shell weight was the strongest predictor of maturity with a correlation of 0.63 and accounted for over 50% of Random Forest feature importance. 

### Finding 2

Water temperature demonstratd almsot no relationship with maturity (correlation = -0.022).

### Finding 3 

Mid-Atlantic populations exhibited the higest average maturity levels among sampled regions. 

### Finding 4 

Biological characteristics explained maturity differences more effectively than environmental temperature. 

## Machine Learning Results
Random Forest Regression
R^2 Score: 0.53
The model successfully captured meaningful relationships between physical charac teristics adn ring count.

## Visualizations

### Correlation Heatmap
visualizations/shell_weight_vs_rings.png
### Shell Weight vs Rings
visualizations/correlation_heatmap.png
### Feature Importance
visualizations/feature_importance.png
### Actual vs Predicted
visualizations/actual_vs_predicted.png

