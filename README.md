# Heart Disease Classification Analysis

Evaluates Random Forest, Logistic Regression, Decision Tree, SVM, Gaussian Naive Bayes, and Gradient Boosting for classifying heart-disease records. The notebook combines exploratory analysis, model training, confusion matrices, and accuracy comparison.

## Workflow

1. Load and inspect `HeartDiseases.csv`.
2. Separate clinical predictors from the `heart disease` target.
3. Create training and testing partitions.
4. Train six classification algorithms.
5. Compare accuracy, classification reports, and confusion matrices.

## Data Requirements

- `HeartDiseases.csv` — clinical features and a heart-disease label.

Datasets and generated artifacts are not included unless they are embedded directly in the notebook.

## Requirements

- pandas
- scikit-learn
- Matplotlib
- Seaborn

Install missing packages in your Jupyter or Google Colab environment before running the notebook.

## Running the Notebook

1. Open [`Heart_Diseases_Classification_Analysis_Random_Forest.ipynb`](Heart_Diseases_Classification_Analysis_Random_Forest.ipynb) in Jupyter Notebook or Google Colab.
2. Place any required data files in the path expected by the notebook.
3. Update local or Google Drive paths where needed.
4. Run the cells from top to bottom.

## Outputs

- Model accuracy comparison
- Confusion matrices
- Classification reports
- Best-model discussion

## Repository Contents

```text
.
|-- README.md
`-- Heart_Diseases_Classification_Analysis_Random_Forest.ipynb
```

## Notes

- This repository preserves the analysis as a notebook-first educational project.
- Results may vary with dataset versions, random splits, package versions, and available hardware.
- Review file paths and runtime-specific commands before executing outside Google Colab.
