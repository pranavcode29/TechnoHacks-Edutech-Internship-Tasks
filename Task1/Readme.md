# This is a Machine Learning Internship Task 1 at TecnoHacks Edutech.
## Task : Wine Quality Prediction

## About the Dataset
The dataset used here is the Red wine quality dataset. This dataset is taken from the UCI machine learning repository, https://archive.ics.uci.edu/ml/datasets/wine+quality.

The dataset contains 1599 rows and 12 columns. The columns are as follows:

Input variables (based on physicochemical tests):

    1. Fixed Acidity - Refers to the concentration of non-volatile acids in a wine. It contributes to the overall tartness or sourness of the wine and is an important factor in determining its taste profile.
    
    2. Volatile Acidity - Represents the presence of volatile acids, primarily acetic acid, in a wine. Higher levels of volatile acidity can give a vinegar-like off-flavor and are generally considered undesirable.
    
    3. Citric Acid - A natural acid found in citrus fruits, citric acid can be present in wines as well. It adds freshness and a citrusy flavor, often contributing to the overall balance and complexity of the wine.
    
    4. Residual Sugar - Refers to the amount of sugar remaining in the wine after fermentation. It contributes to the sweetness of the wine and can range from dry (very little residual sugar) to sweet (higher residual sugar levels).
    
    5. Chlorides - Represents the concentration of salt in the wine. High levels of chlorides can contribute to a salty taste, which is generally undesirable in wine.
    
    6. Free Sulfur Dioxide - Sulfur dioxide is commonly used as a preservative in winemaking. Free sulfur dioxide refers to the amount of sulfur dioxide that is not bound to other compounds. It helps prevent oxidation and microbial spoilage in wine.
    
   7. Total Sulfur Dioxide - Represents the total amount of both free and bound sulfur dioxide in the wine. It is an important parameter for assessing the wine's stability and preservation.
    
   8. Density - Refers to the mass of the wine per unit volume. It is influenced by factors such as sugar content, alcohol content, and overall composition, and can provide insights into the wine's body and richness.
    
    9. PH - Represents the level of acidity or alkalinity in a wine on a logarithmic scale. Lower pH values indicate higher acidity, while higher pH values indicate lower acidity. pH plays a crucial role in determining the overall balance and stability of the wine.
    
    10. Sulphates - Refers to the concentration of sulfur-containing compounds, such as sulfites, in the wine. Sulphates can act as antioxidants and preservatives, helping to maintain the wine's freshness and prevent spoilage.
    
    11. Alcohol - Represents the percentage of alcohol by volume in the wine. It contributes to the wine's body, texture, and overall perception of warmth or heat.

Output variable (based on sensory data):

   12.  Quality (score between 0 and 10) - A score between 0 and 10 based on sensory evaluation data. It represents the overall subjective assessment of the wine's quality, taking into account various factors such as aroma, taste, balance, complexity, and overall enjoyment.

## Objective of the Task

In this task, we have to predict the quality of red wine based on the physicochemical tests.

## Steps perfromed in this Task 

1. Data Exploration
2. Data Cleaning and Data Preprocessing
3. Descriptive Statistical Analysis
4. Data Visualization
5. Selecting Independent and Dependent Variable and Train Test split
6. Normalization of Data
7. Building ML Classification Model ( I have used classification algorithms instead of regression by classifying quality as more than or equal to 7 as good and rest as bad)
8. Generating Prediction
9. Evaulating Accuracy and AUC Score
10. Got RandomForest Classifier as the best model with 89.6 % of Auc Score.
    
