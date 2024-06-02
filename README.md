<div align="center">
  <h1>
    Air Quality Prediction in an Italian City
  </h1>

<h4>
  <a href="https://caheras.github.io">More info</a>
</h4>

[![GitHub Slrosales](https://img.shields.io/badge/by-Slrosales-purple)](https://github.com/Slrosales)
[![GitHub Rubens1414](https://img.shields.io/badge/by-caheras-blue)](https://github.com/caheras)

</div>

## Overview
This project focuses on predicting air quality in an Italian city using historical data on meteorological variables and atmospheric pollutants. By applying linear regression and neural network models, the goal is to improve the monitoring and management of air quality, thus protecting public health and the environment.

## Motivation
Italy, like many other countries, faces significant air quality challenges, especially in densely populated urban areas. This project aims to address these local problems by developing predictive models tailored to the specific needs and characteristics of the region. The availability of public air quality data from government agencies and organizations in Italy facilitated this research.

## Objectives
1. **General Objective**: Predict the concentration of harmful contaminants and particles in the air using linear regression and neural network models.
2. **Specific Objectives**:
   - Predict carbon monoxide (CO) concentration using variables such as non-metallic hydrocarbons, NOx, temperature, and humidity.
   - Predict benzene (C6H6) concentration using variables like non-metallic hydrocarbons, NOx, ozone, temperature, and humidity.
   - Predict nitrogen oxide (NOx) concentration using variables such as non-metallic hydrocarbons, carbon monoxide, ozone, temperature, and humidity.

## Methodology
### Data Cleaning
Cleaning the dataset improved data quality, reduced multicollinearity, and facilitated the stability and generalization of predictive models. A correlation matrix was used to analyze relationships between variables.

### Model Selection and Validation
- **Linear Regression**:
  - Chosen for its clarity and efficiency in establishing linear relationships.
  - Data was split into training (70%) and validation (30%) sets.
  - K-fold cross-validation was used to enhance accuracy.
  - Results:
    - CO Model: Accuracy of 87.74%, mean R² of 86%.
    - NOx Model: Accuracy of 78%, mean R² of 78%.
    - C6H6 Model: Accuracy of 93.80%, mean R² of 94%.

- **Neural Networks**:
  - Chosen for their ability to capture complex, non-linear relationships.
  - Similar data split and K-fold cross-validation as linear regression.
  - Results:
    - Best architectures achieved higher R² scores and lower MSE and MAE values.
    - CO Model: Best architecture (15, 15) with mean R² of 87.74%.
    - NOx Model: Best architecture (15, 15) with mean R² of 84.97%.
    - C6H6 Model: Best architecture (10, 10, 10) with mean R² of 96.89%.

## Results
- **Linear Regression** provided a good baseline with consistent performance across different models.
- **Neural Networks** demonstrated superior predictive power, capturing intricate patterns between input variables and pollutant levels.

## Conclusions
Advanced machine learning models, particularly neural networks, significantly enhance the prediction and management of urban air quality. This can lead to timely preventive and corrective actions, mitigating the health effects of pollutants and protecting the environment. However, linear regression remains a viable option in resource-constrained scenarios.

## Team
- **Laura Gómez Rosales (Leader)**: Systems Engineering student with an interest in Computer Vision and leadership skills.
- **Camilo Heras Gómez**: Systems Engineering student, known for his willingness to help and interest in computer graphics and networking.


