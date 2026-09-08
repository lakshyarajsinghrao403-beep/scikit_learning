# Scikit-learn Learning Journey

A hands-on collection of Jupyter notebooks for learning core machine-learning workflows with Python and [scikit-learn](https://scikit-learn.org/). Each notebook focuses on one concept, from preparing data to training, evaluating, and tuning classification and regression models.

## What you'll find

- Data splitting, missing-value imputation, feature scaling, and categorical encoding
- Column-wise preprocessing with `make_column_transformer`
- Regression and classification with linear regression, logistic regression, KNN, decision trees, and support vector machines
- Model evaluation with confusion matrices, classification reports, K-fold cross-validation, and `cross_val_score`
- Hyperparameter tuning with `GridSearchCV` and `RandomizedSearchCV`

## Repository structure

| Notebook | Topic |
| --- | --- |
| `train_test_split.ipynb` | Splitting a dataset into training and test sets |
| `simple_imputer.ipynb` | Handling missing values with `SimpleImputer` |
| `featurescaling.ipynb` | Standardization with `StandardScaler` and normalization with `MinMaxScaler` |
| `onehotencoding.ipynb` | Encoding nominal categories with `OneHotEncoder` |
| `ordinalencoding.ipynb` | Encoding ordered categories with `OrdinalEncoder` |
| `columntransformer.ipynb` | Applying different transformations to selected columns |
| `linear_regression.ipynb` | Linear-regression fundamentals |
| `logisticregression.ipynb` | Binary classification with logistic regression |
| `logistic_multiclass.ipynb` | Multiclass classification with logistic regression on the digits dataset |
| `KNN.ipynb` | K-nearest-neighbours classification and evaluation |
| `decisiontree.ipynb` | Decision-tree classification and evaluation |
| `supportvectormachine.ipynb` | Support vector machine classification on the Iris dataset |
| `K-foldcrossvalidation.ipynb` | K-fold cross-validation and `cross_val_score` |
| `GridSearchCV.ipynb` | Grid-search hyperparameter tuning for an SVM |
| `RandomSearchCV.ipynb` | Randomized-search hyperparameter tuning for an SVM |

## Datasets

- `500hits.csv` — local practice dataset used in the train/test split, feature-scaling, KNN, and decision-tree notebooks.
- Built-in scikit-learn datasets — the Iris and digits datasets are used in selected notebooks.
- Seaborn's Iris dataset — used in the hyperparameter-tuning notebooks; it is fetched when the notebooks run.

## Getting started

### 1. Clone the repository

```bash
git clone <your-repository-url>
cd scikit_learn
```

### 2. Create and activate a virtual environment

```bash
python -m venv .venv
```

**Windows (PowerShell)**

```powershell
.venv\Scripts\Activate.ps1
```

**macOS/Linux**

```bash
source .venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter

```bash
jupyter notebook
```

Open any `.ipynb` file and run its cells from top to bottom. A few notebooks download example datasets, so an internet connection may be needed the first time they run.

## Requirements

The project uses Python with Jupyter, NumPy, pandas, Matplotlib, Seaborn, and scikit-learn. The complete dependency list is in [`requirements.txt`](requirements.txt).

## Notes

This is a learning repository focused on small, clear experiments rather than production-ready pipelines. The notebooks are designed to be explored independently, though working through them in the order listed above will give the smoothest progression.
