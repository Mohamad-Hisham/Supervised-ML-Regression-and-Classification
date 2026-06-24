# Supervised ML: Regression and Classification

A structured, notebook-first machine learning study project covering the foundations of supervised learning through clear explanations, NumPy implementations, and visualization-focused helpers.

## Overview

This repository is centered around a single main notebook:

- `Supervised ML Regression and Classification.ipynb`

The notebook walks through core supervised machine learning concepts from first principles, with supporting Python utilities for plotting, intuition, and experimentation. It is designed as an educational resource rather than a production ML package.

The project covers:

- machine learning fundamentals
- supervised learning concepts
- univariate linear regression
- cost functions and gradient descent
- multiple linear regression
- vectorization
- feature scaling and feature engineering
- logistic regression
- decision boundaries
- overfitting, underfitting, and regularization

## Project Highlights

- Clean, structured learning notebook from regression basics to classification
- Core algorithms implemented from scratch using `NumPy`
- Visual explanations with custom `Matplotlib` plots
- Comparisons and examples using `scikit-learn`
- Included helper modules, datasets, and images for a self-contained learning workflow

## Notebook Roadmap

| Section | Topics |
| --- | --- |
| `1. Introduction to Machine Learning` | What ML is, supervised learning, regression vs classification |
| `1.4 Linear Regression` | Model intuition, cost function, gradient descent, implementation |
| `2. Regression with multiple input variables` | Vectorization, multivariate regression, feature scaling, feature engineering |
| `3. Classification` | Logistic regression, decision boundaries, logistic loss, overfitting, regularization |

## Repository Structure

```text
.
|-- Supervised ML Regression and Classification.ipynb
|-- README.md
|-- data/
|   |-- houses.txt
|-- images/
|-- deeplearning.mplstyle
|-- data.txt
|-- lab_utils_common_Part1.py
|-- lab_utils_common_Part2.py
|-- lab_utils_common_Part3.py
|-- lab_utils_multi.py
|-- lab_utils_uni.py
|-- plt_logistic_loss.py
|-- plt_one_addpt_onclick.py
|-- plt_overfit.py
|-- plt_quad_logistic.py
```

## Key Files

| File | Purpose |
| --- | --- |
| `Supervised ML Regression and Classification.ipynb` | Main learning notebook |
| `lab_utils_uni.py` | Utilities for univariate linear regression explanations and plots |
| `lab_utils_multi.py` | Utilities for multivariable regression content |
| `lab_utils_common_Part1.py` | Shared helpers for early regression sections |
| `lab_utils_common_Part2.py` | Shared helpers for multiple-variable regression sections |
| `lab_utils_common_Part3.py` | Shared helpers for logistic regression and classification |
| `plt_overfit.py` | Visual tools for overfitting and regularization demonstrations |
| `plt_logistic_loss.py` | Visualizations for logistic cost behavior |
| `data.txt` and `data/houses.txt` | Example datasets used throughout the notebook |
| `images/` | Figures embedded in the notebook |

## Requirements

To run the notebook smoothly, install:

- Python 3.10+
- Jupyter Notebook or JupyterLab
- `numpy`
- `matplotlib`
- `scipy`
- `scikit-learn`
- `ipywidgets`

## Quick Start

1. Clone the repository:

```bash
git clone https://github.com/Mohamad-Hisham/Supervised-ML-Regression-and-Classification.git
cd Supervised-ML-Regression-and-Classification
```

2. Create and activate a virtual environment:

```bash
python -m venv .venv
```

Windows:

```bash
.venv\Scripts\activate
```

macOS/Linux:

```bash
source .venv/bin/activate
```

3. Install dependencies:

```bash
pip install numpy matplotlib scipy scikit-learn ipywidgets notebook
```

4. Launch Jupyter:

```bash
jupyter notebook
```

5. Open:

```text
Supervised ML Regression and Classification.ipynb
```

## Learning Approach

This repository is best used as a hands-on study resource:

- read the theory in the notebook
- inspect the code implementations
- run the cells step by step
- experiment with parameters and datasets
- compare from-scratch logic with `scikit-learn` usage

## Notes

- This project is educational and notebook-driven.
- Several helper scripts are focused on visualization and interactive explanation rather than general-purpose reuse.
- Some utilities are adapted for the structure of this notebook, so keeping the current folder layout is recommended.

## Suggested Improvements

If you want to expand the repository later, good next additions would be:

- a `requirements.txt`
- a `LICENSE`
- exported notebook screenshots in the README
- separate notebooks for regression and classification
- exercises or practice tasks for each section

## Author

Created as a personal machine learning study and notes repository focused on building intuition for supervised learning, regression, and classification.
