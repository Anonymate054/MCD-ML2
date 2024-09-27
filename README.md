---

<h1 align="center">
  <br>
  <b>MCD - Machine Learning 2</b>
  <br>
</h1>

<p align="center">
  Credit Risk Classification Model.
  <br>
</p>


## Description

In this project, we develop a machine learning model to classify loan applicants and predict the probability of loan default. The model is designed to be robust and interpretable, providing insights into its predictions to aid in decision-making.

## Authors

- **Noguera Gil, Luis Enrique.**  
- **Sepúlveda Furber, Miguel Enrique.**  
- **Galicia Agonizante, Adrian.**  
- **Rivera Ruiz, Mariel.**  

## Technologies Used

- Python 3 ![Python](https://img.shields.io/badge/Python-3.11-blue)
- Jupyter Notebooks
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Project Objective

The objective of this project is to develop a classification model that predicts the likelihood of loan default for applicants. The model aims to be empirically robust and interpretable, particularly in cases of loan rejection, enabling banks to make informed, fair decisions while minimizing financial risk and optimizing loan portfolios.

## Analysis Section

The project consists of several stages, including data exploration, feature engineering, model development, and evaluation. The dataset includes financial and personal information on loan applicants, with the target variable being whether or not the applicant defaulted on their loan.

1. **Data Exploration:** Analyze the dataset for patterns and relationships between features.
2. **Feature Engineering:** Create new features that may enhance model performance.
3. **Model Development:** Train and evaluate multiple classification algorithms such as logistic regression, decision trees, random forests, and XGBoost.
4. **Interpretability:** Use techniques like SHAP (SHapley Additive exPlanations) to interpret model predictions.
5. **Evaluation:** Assess model performance using metrics like accuracy, precision, recall, and AUC-ROC.

## Prerequisites

- [Anaconda](https://www.anaconda.com/download/) >=4.x
- Optional [Mamba](https://mamba.readthedocs.io/en/latest/)

## Create Environment

```bash
conda env create -f environment.yml
activate ML2
```

or 

```bash
conda install -c conda-forge mamba
mamba env create -f environment.yml
activate ML2
```

## Modules and Default Modules

To install the default modules located in the `scripts` directory, use the following command:

```bash
pip install --editable .
```

For more information about the user's modules, refer to `install.md`.

## The Resulting Directory Structure

The directory structure of your project will look something like this (depending on the settings that you choose):

```
├── LICENSE            <- Open-source license if one is chosen
├── README.md          <- The top-level README for developers using this project.
├── module         <- User module directory
├── data
│   ├── external       <- Data from third-party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- Documentation generated with mkdocs
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-anony-initial-data-exploration`.
│
├── scripts            <- Default modules and scripts for the project
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
```

---

Feel free to add more details or sections as needed!
