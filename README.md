# Healthcare Survival Analysis: Heart Attack Patients
This repository contains a Jupyter Notebook performing survival analysis on the Worcester Heart Attack Study (WHAS500) dataset. The analysis explores classical and machine learning approaches to model time-to-event outcomes for patients hospitalized with acute myocardial infarction.

## Analysis Workflow

The notebook covers the following steps:

1.  **Load and Inspect Data**: Loads the WHAS500 dataset and prepares variables for modeling.
2.  **Kaplan-Meier Estimation**: Estimates and visualizes survival curves, comparing survival across subgroups.
3.  **Cox Proportional Hazards Model**: Fits a classical Cox model, interprets hazard ratios, and visualizes adjusted curves.
4.  **Evaluating Performance: The Concordance Index**: Assesses model discrimination ability using the concordance index (C-index).
5.  **Random Survival Forests**: Models nonlinear survival patterns and visualizes predicted survival curves for different groups.
6.  **DeepSurv: Deep Learning for Survival Analysis**: Applies a neural network to capture complex risk relationships and compares model performance.
7.  **Summary and Interpretation**: Compares all models, interprets findings, and discusses trade-offs between interpretability and flexibility.

## Notebook

-   [`survival_analysis_heart_attack_patients.ipynb`](survival_analysis_heart_attack_patients.ipynb): Contains the complete analysis, from data loading and preprocessing to model building, evaluation, and interpretation.


## Setup

To run the notebook, you will need Python and the libraries listed in the notebook, primarily:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-survival
- lifelines
- pycox
- torchtuples

You can typically install these using pip:
```sh
pip install pandas numpy matplotlib seaborn scikit-survival lifelines pycox torchtuples
```
The notebook [`setup_check.ipynb`](setup_check.ipynb) can be used to verify that your Python environment is ready.