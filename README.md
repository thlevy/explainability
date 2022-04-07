# Notebooks for POC on ML explainability
It includes multiple notebooks to demonstrate Machine Learning explainability:
* Comparison of various explanation methods (in particular LIME & SHAP) for classification with tabular data
* Explainability with SHAP for classification with numerical and categorical data  
* Basic explainability of text classifications
* Basic explainability of product classifications

## Requirements
It has been tested with the following Python 3 libraries installed:
* scikit-learn
* lime
* shap
* [shapash](https://github.com/MAIF/shapash)

NOTE: Shap API is changing. You may need to slightly adapt the code if you want to run the notebooks with different SHAP versions!
It is recommended to use poetry to manage dependencies in a simple way (see section below)

## To setup & run with poetry dependency management (recommended)

* install [poetry](https://python-poetry.org/docs/)
* run `poetry install`

To run notebooks (with local jupyter server):
* run `poetry run jupyter notebook`

Or to run (with VS Code):
* run `poetry shell` and `code .`