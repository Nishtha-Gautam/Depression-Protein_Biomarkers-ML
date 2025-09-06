# Depression-Protein_Biomarkers-ML
Machine learning study on protein biomarkers for depression classification — project conducted under CSIR-IGIB.

Project Overview<br>
This project was carried out at CSIR-IGIB. Due to data confidentiality, the original dataset and results cannot be shared here. Instead, a similar workflow with dummy models is provided to showcase the methodology.
The actual dataset contained 2800+ protein biomarkers. The workflow involved imputation, preprocessing, feature selection, model building, and evaluation.

Methodology- <br>
Data Preprocessing: MICE imputation → Standardization → Exploratory Data Analysis (EDA) <br>
Feature Selection: LASSO feature selection → Top 110 features retained <br>
Model Training & Evaluation: Train (80%)-test (20%) split → Logistic Regression (LR) → Support Vector Machine (SVM) → Multi-Layer Perceptron (MLP) → Hyperparameter tuning

Models used:
Logistic Regression (LR),
Support Vector Machine (SVM),
Multi-Layer Perceptron (MLP)
(Hyperparameter tuning performed for each)

## Results

Logistic Regression (LR):  
Best performance among models  
ROC-AUC: 0.87  

Support Vector Machine (SVM):  
Closely followed LR in discrimination ability  
ROC-AUC: 0.85  

Multi-Layer Perceptron (MLP):  
Underperformed compared to LR and SVM  
ROC-AUC: 0.78  

### ROC-AUC Curve Comparison
<p align="center">
  <img src="https://github.com/Nishtha-Gautam/Depression-Protein_Biomarkers-ML/blob/main/ROC-AUC.png" alt="ROC-AUC Curve Comparison" width="600"/>
</p>

**Observation:**  
The convergence of GFAP, PDP1, and CREG1 across models supports their potential as robust biomarkers for depression subtypes and offers promising directions for precision psychiatry.

Limitations<br>
The original dataset and results cannot be shared due to confidentiality.<br>
Dummy models are shown here to replicate the workflow.

License<br>
All rights reserved. This project is part of CSIR-IGIB and the code/data may not be reused without permission.
