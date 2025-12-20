# Stroke-prediction-using-R


End-to-end stroke prediction model built and deployed using R and tidymodels

The project involves building an end-to-end machine learning model to predict the risk of stroke occurrence based on clinical and demographic input data. The project was undertaken as part of an applied data science course offered on Coursera.

# Dataset

The data set comprises patient-level information regarding age, gender, hypertension, heart disease, BMI, smoking status, and average glucose levels with stroke as the target.

# Methodology
- Data Preprocessing and Feature Engineering using `recipes` package
- Missing values and categorical encoding
- Handling Imbalanced Classes Through Resampling
- Model training with Random Forest (ranger)
- Evaluation des modèles parcross-validation et des indicateurs ROC
- Persistence with `saveRDS()` and inference with `readRDS()`

## Deployment
The trained model can be used for loading and predicting the risks of strokes in new patients without the need for model retraining.

## Tools
- R
- tidymodel
- recipes 
- ranger
- ggplot2
-
- ## Output > The last output will be a developed stroke risk assessment model and also an inference pipeline that can be applied.
