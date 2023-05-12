# XAI Gasification Modelling

# 1. Description of the project

In this project seven different types of regression-based predictive modelling techniques are used to predict the product gas composition (H<sub>2</sub> , CO, CO<sub>2</sub>, CH<sub>4</sub>) and gas yield (GY) during the gasification of biomass in a fluidised bed reactor. The performance of Linear Regression (LR), Multilayer perception (MLP), Ridge Regression (RR), Least-angle regression (LARS), Random Forest (RF), Bagging (BAG) and gradient boosting model (GB) regression-based models are compared. It was found that a **GB-based model** with a learning rate of 0.01 and number of boosting stages of 1000 yielded the best result. **SHapley Additive exPlanations (SHAP)**-based explainable artificial intelligence (XAI) method was utilised to explain individual predictions. The outcome of this project indicates that XAI-based methodology can be used as a viable alternative modelling paradigm in predicting the performance of a fluidised bed gasifier for an informed decision-making process.

# 2. Notebook description

This project has three Jupyter notebook files.

**a. Gasification_model_XAI.ipynb**- This file contains scripts for training and predicting the product gas composition while also carrying out post-hoc explainability analysis using SHAP to interpret the prediction of the behaviour of the training GB model. 

**b. Gasification_model_comparison.ipynb**- This file contains scripts that compares the performance of the GB based regression model with LR, RR, LARS, RF, and BAG-based regression models. This file also contains analysis to find the optimal parameters that would yield the best prediction. 

**c. Gasification_model_MLP.ipynb**- This file contains scripts that compares the performance of the GB based regression model with MLP based regression models.

# 3. Dependencies 

- NumPy
- Pandas
- SciPy
- Scikit-learn
- SHAP

# 4. Citation

The results of this project was submitted in Fuel (Elsevier). Currently, the paper is under review.
