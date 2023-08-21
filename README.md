# LIME-SHAP-Evaluation

The aim of this project is to evaluate the LIME (Local Interpretable Model-agnostic Explanations) and SHAP (SHapley Additive exPlanations) both quantitatively using the LEAF framework (Local Explanation evAluation Framework) and qualitatively by interpreting the LIME and SHAP explanation.

## To run the code, follow these steps:
- Clone this repository to your local machine.
- Install Libraries in your environment using pip install ```-r requirements.txt```
- Load the dataset from: https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri
-  Place the dataset in the "Archive" folder within the project directory. Ensure that the dataset is properly located:
  ```bash
    Project
    ├── Archive/
    │ ├── dataset_file.csv
    ├── ...
```
- That's it! Now you're ready to run the code.

- ## Steps for Qualitative Evaluation
- Re-processing data
- Building the Black-Box Models
- Classification the images with the Black-Box-Modells
- Explaining the Decisions of the Black-Box Models Using LIME and SHAP

## Steps for Quanitativ Evaluation
- Re-processing data
- Converting the images into a tabular form
- Building the Black-Box Models
- Classification the tabular data with the Black-Box Models
- Using LEAF to Calculate the stability and the fidelity in order to evaluate LIME & SHAP
