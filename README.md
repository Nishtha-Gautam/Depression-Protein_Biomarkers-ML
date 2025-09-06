# Depression-Protein_Biomarkers-ML
Machine learning study on protein biomarkers for depression classification — project conducted under CSIR-IGIB.

Project Overview
This project was carried out at CSIR-IGIB. Due to data confidentiality, the original dataset and results cannot be shared here. Instead, a similar workflow with dummy models is provided to showcase the methodology.
The actual dataset contained 2800+ protein biomarkers. The workflow involved imputation, preprocessing, feature selection, model building, and evaluation.

Methodology

Data Preprocessing
MICE imputation for missing values
Standardization of features
Exploratory Data Analysis (EDA)
Feature Selection: LASSO feature selection. Reduced to top 110 features
Model Training & Evaluation
Dataset split into training (80%) and testing sets (20%)

Models used:
Logistic Regression (LR)
Support Vector Machine (SVM)
Multi-Layer Perceptron (MLP)
Hyperparameter tuning performed for each

Results
Logistic Regression achieved the best discrimination between subtypes, closely followed by SVM.
MLP underperformed compared to LR and SVM.
Key biomarkers identified:
GFAP, PDP1, and CREG1 → consistently important across models (linked to neuroinflammation, energy metabolism, and cellular regulation). The convergence of these markers across models supports their potential as biomarkers for depression subtypes, offering promising directions for precision psychiatry.

Limitations
The original dataset and results cannot be shared due to confidentiality.
Dummy models are shown here to replicate the workflow.

License
All rights reserved. This project is part of CSIR-IGIB and the code/data may not be reused without permission.
