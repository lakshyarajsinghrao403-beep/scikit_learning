# Scikit-learn Learning Journey

A hands-on collection of Jupyter notebooks created while learning machine learning with Python and [scikit-learn](https://scikit-learn.org/).

## Topics covered

### Data preparation

- Train/test splitting
- Handling missing values with `SimpleImputer`
- Feature scaling with `StandardScaler` and `MinMaxScaler`
- One-hot and ordinal encoding
- Column transformations

### Machine-learning models

- Linear regression
- Logistic regression
- K-nearest neighbours (KNN)
- Decision trees
- Random forests

The classification notebooks also explore evaluation tools such as confusion matrices and classification reports.

## Getting started

1. Clone this repository and open its folder.
2. Create and activate a virtual environment (recommended).
3. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open any `.ipynb` file and run the cells in order.

## Repository contents

| File | What it covers |
| --- | --- |
| `train_test_split.ipynb` | Splitting a dataset for training and testing |
| `simple_imputer.ipynb` | Filling in missing values |
| `featurescaling.ipynb` | Standardization and normalization |
| `onehotencoding.ipynb` / `ordinalencoding.ipynb` | Encoding categorical features |
| `columntransformer.ipynb` | Applying transformations to selected columns |
| `linear_regression.ipynb` | Linear regression |
| `logisticregression.ipynb` | Logistic-regression classification |
| `KNN.ipynb` | K-nearest-neighbours classification |
| `decisiontree.ipynb` | Decision-tree classification |
| `randomforest.ipynb` | Random-forest classification |

## Dataset

`500hits.csv` is used by selected notebooks for practice.

## Notes

This is a learning repository. The notebooks prioritize clear experimentation and practice over production-ready machine-learning pipelines.

## there are more topics and lot to cover in this journey yet.