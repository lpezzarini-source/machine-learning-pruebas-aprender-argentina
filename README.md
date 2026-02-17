
# Machine Learning Analysis of School Performance in Argentina (Aprender)

This repository contains the code and documentation for my Master’s thesis for the **MSc in Data Science at Universidad de San Andrés**.

The project applies **machine learning techniques** (Random Forest and XGBoost) to analyze the determinants of school performance in Argentina using data from the **National Aprender Assessment (2023)**. The main outcome variable is the percentage of students per school achieving satisfactory or advanced performance in Language and Mathematics.

To enhance interpretability, the analysis relies on **SHAP values**, allowing the identification and decomposition of the contribution of more than 120 predictors across five broad dimensions:
- Household factors  
- Individual factors  
- School trajectory factors  
- Institutional factors  
- Contextual factors  

## Repository structure

- `inputs/`  
  Raw microdata  and processed datasets used in the analysis.   IMPORTAN: Due to the file size, the student raw database could not be uploaded. It can be found at the following link:https://drive.google.com/drive/folders/1vit7q4sz8VN6nwTKGDYo4Lo-qayxf8yX?usp=drive_link
  
- `scripts/`  
  Python scripts used for data preparation and model training.

- `outputs/`  
  Figures, tables, and intermediate results used in the thesis. IMPORTAN: Due to the file size, the student data could not be uploaded. The database can be found at the following link:https://drive.google.com/drive/folders/1vit7q4sz8VN6nwTKGDYo4Lo-qayxf8yX?usp=drive_link

- `docs/`  
  Supporting documentation, including variable dictionaries and supplementary materials.

## Author

Lucía Pezzarini  
