# Notebooks for POC on ML explainability
It includes multiple notebooks to demonstrate Machine Learning explainability:
* Comparison of various explanation methods (in particular LIME & SHAP) for classification with tabular data
* Explainability with SHAP for classification with numerical and categorical data  
* Basic explainability of text classifications
* Basic explainability of product classifications

## Requirements
It has been tested with the following Python 3 libraries installed:
* scikit-learn              0.23.2
* lime                      0.2.0.1 (only for comparison)
* shap                      0.35.0 (or 0.37.0 for text & product classifications)

NOTE: Shap API is changing. You may need to slightly adapt the code if you want to run the notebooks with different SHAP versions!
