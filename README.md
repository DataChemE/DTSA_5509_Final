# DTSA_5509_Final

# Diabetes Prediction Project

## Project Overview

This project leverages a Gradient Boosting Classifier to predict the presence of diabetes, utilizing a dataset based on health indicators and diabetes outcomes. Through comprehensive data preprocessing, feature selection, and model optimization phases, we have developed a predictive model that offers meaningful insights into an individual's risk of diabetes based on a variety of health-related factors.

## Dataset

Our analysis is grounded in data from the Behavioral Risk Factor Surveillance System (BRFSS), featuring over 250,000 responses. The dataset includes 21 predictors that cover a range of health behaviors, health outcomes, and demographic details. The target variable, `Diabetes_binary`, signifies the presence (1) or absence (0) of diabetes or prediabetes in respondents, aiming to provide a nuanced understanding of diabetes risk factors across a diverse population.

## Key Features

- **Data Preprocessing**: The project begins with a rigorous exploration and cleaning of the data. We address class imbalances and normalize features to prepare the dataset for effective modeling.

- **Feature Selection**: Utilizing backward elimination, we carefully refine our set of predictors, prioritizing variables that are statistically significant. This step ensures that our model focuses on the most impactful factors influencing diabetes risk.

- **Model Optimization**: The core of our project revolves around the sequential tuning of the Gradient Boosting Classifier's parameters. Our objective is to enhance the model's ROC AUC scores, reflecting its ability to accurately identify individuals at risk for diabetes. This optimization process involves adjusting parameters such as the learning rate, number of estimators, and tree depth to strike a balance between model complexity and predictive accuracy.
