# Yandex ML Tutorials

My solutions to tutorial notebooks and homework assignments from Yandex ML School (Uzbekistan).
The exercises and notebook structure belong to the course; the solutions are my own.

## Structure

| Folder | Content | Status |
|---|---|---|
| `ml/` | Machine Learning tutorial notebooks | In progress |
| `homeworks/` | Graded homework assignments | In progress |

## Machine Learning (`ml/`)

| # | Notebook | Topics |
|---|---|---|
| 01 | `week0_01_01_ml_workflow_and_baseline.ipynb` | ML workflow, train/test split, baseline models |
| 02 | `week0_01_02_knn_practice.ipynb` | k-Nearest Neighbors, distance metrics |
| 03 | `week0_02_01_linear_regression.ipynb` | Linear regression, least squares, MSE |
| 04 | `week0_03_01_regularisation_and_validation.ipynb` | Regularisation (L1/L2), validation, cross-validation |

## Homeworks (`homeworks/`)

| # | Folder | Files | Topics |
|---|---|---|---|
| 01 | `homework1/` | `k_nearest_neighbor.py`, `knn_assignment_0_01.ipynb` | kNN classifier from scratch, L2 distance (two-loop / one-loop / fully vectorized), vectorization speedups, comparison with scikit-learn |

Homework 1 is based on [Stanford CS231n Assignment 1](http://cs231n.github.io/assignments2019/assignment1/).

## Setup

```bash
pip install numpy pandas matplotlib scikit-learn
```

Open the notebooks in VS Code (Jupyter extension) or with `jupyter notebook`.
For homeworks, run the notebook from inside its folder so it can import the `.py` file.