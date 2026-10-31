# Diabetes Risk Analysis | Belgium Campus
A group project completed for the **MLG382 Machine Learning module** at Belgium Campus ITversity.

This project explores health and lifestyle indicators associated with diabetes through exploratory data analysis, a Dash interface prototype and technical documentation.

## Project Overview
The project investigates how health and lifestyle data can support diabetes risk classification, patient segmentation and interpretable predictions.

The notebook contains exploratory analysis and an early application prototype. The technical report describes the broader modelling solution developed during the project.

## Included Work
- Loading and inspecting an Excel dataset.
- Checking for duplicate records.
- Exploring descriptive statistics and visualisations.
- Building a Dash interface accepting glucose, BMI and age.
- Documenting classification, clustering and model explanation approaches.

## Technology Stack
**Notebook:** Python, pandas, NumPy, matplotlib, seaborn, scikit-learn, Dash and Jupyter Notebook.

**Additional methods discussed in the report:** XGBoost, K-means clustering and SHAP.

## Repository Files
| File | Description |
|---|---|
| `README.md` | Project overview and setup instructions |
| `MLG382.ipynb` | Exploratory analysis and Dash prototype |
| `DataSet.xlsx` | Input dataset, where redistribution is permitted |
| `docs/technical-report.pdf` | Project approach, reported findings and recommendations |

## Run the Notebook
Install the required packages:

```bash
python -m pip install jupyter pandas numpy matplotlib seaborn scikit-learn dash dash-ag-grid openpyxl
```

Place `DataSet.xlsx` in the same folder as `MLG382.ipynb`. The notebook reads this exact filename.

Launch Jupyter:

```bash
jupyter notebook
```

Open `MLG382.ipynb` and review the cells in order. The notebook includes package-installation cells and a cell that launches the Dash prototype.

If the dataset is not included in the repository, it must be obtained separately before running the data-analysis cells.

## Prototype Status
The Dash prototype uses a manually defined formula based on glucose, BMI and age to display a risk category.

It does not use a trained classifier. Its output demonstrates the interface and callback workflow and is not a validated medical prediction.

## Approach Described in the Report
The technical report discusses:
- Comparing Decision Tree, Random Forest and XGBoost classifiers.
- Selecting XGBoost as the final classifier.
- Applying K-means clustering with three patient segments.
- Using SHAP to explain factors influencing predictions.
- Presenting results through a decision support interface.

The final training implementation and trained models described in the report are not included in this repository. The report provides qualitative model comparisons rather than a complete numerical evaluation table.

## Limitations and Future Work
- Add the final modelling code and reproducible preprocessing workflow.
- Include numerical evaluation results and baseline comparisons.
- Connect the interface to a validated trained model.
- Document the dataset source and redistribution terms.
- Clearly distinguish development prototypes from final implementations.

This project is an educational demonstration and is not intended for diagnosis or clinical decision-making.

## Academic Context

This repository contains university group coursework shared for portfolio demonstration. The materials represent combined group work and do not imply sole authorship.
