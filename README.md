# Water Potability Prediction

## Overview
Determining whether water is safe for consumption is crucial but often requires laboratory testing, which can be time-consuming and costly. This project leverages machine learning algorithms to predict whether a given water sample is potable based on features such as pH, hardness, conductivity, and chemical composition. The goal is to provide an automated and efficient method for water quality assessment.

## Dataset
The dataset used for this project contains various water quality parameters:

- **pH**: Indicates the acidity or basicity of water.
- **Hardness**: Measures the concentration of calcium and magnesium ions.
- **Solids**: Total dissolved solids in ppm.
- **Chloramines**: Disinfectants used in water treatment.
- **Sulfate**: A key parameter in water taste and safety.
- **Conductivity**: Indicates the ability of water to conduct electricity.
- **Organic Carbon**: Represents the amount of organic material present.
- **Trihalomethanes**: Byproducts of chlorination, which can be harmful.
- **Turbidity**: Measures the clarity of water.
- **Potability**: The target variable (1 = potable, 0 = not potable).

## Objectives
- Understand the distribution of water quality parameters.
- Identify correlations between features.
- Determine key factors influencing water potability.
- Use visualizations to gain insights.
- Train machine learning models to classify water samples as potable or non-potable.

## Methodology
1. **Data Preprocessing**: Handling missing values, scaling, and feature engineering.
2. **Exploratory Data Analysis (EDA)**: Visualizing distributions and relationships between features.
3. **Model Selection & Training**: Implementing various machine learning models (e.g., Decision Trees, Random Forest, Logistic Regression, etc.).
4. **Evaluation**: Assessing model performance using metrics like accuracy, precision, recall, and F1-score.
5. **Prediction & Insights**: Using the trained model to predict water potability.

## Installation & Usage
### Prerequisites
Ensure you have the following installed:
- Python 3.13
- Jupyter Notebook
- Required libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`


## Results
- Summary of key findings and insights from EDA.
- Performance comparison of different machine learning models.
- Final model evaluation and recommendations.

## Future Work
- Enhance model performance with hyperparameter tuning.
- Experiment with deep learning approaches.
- Deploy the model as a web application for real-time predictions.

## License
This project is open-source and available under the MIT License.

## Author
Muhammad Farid Zahin bin Ayub
Muhamad Ariff Syamilan bin Mat Rozik
Zakwan Hafiz bin Zulkafli

Feel free to reach out for collaboration or feedback!

