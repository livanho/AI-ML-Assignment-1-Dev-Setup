# AI-ML-Assignment-1-Dev-Setup
AD331 H11 37160 - F25 - Artificial Intelligence Section 2257_37160 Term: Fall 2025


## Environment and Libraries

This notebook sets up a basic Python data science environment for working with the Iris dataset.

Final environment (to be filled in from your system):

- **Python**: 3.x
- **Key libraries used**:
  - `pandas` (imported as `pd`)  
  - `numpy` (imported as `np`)  
  - `seaborn` (imported as `sns`)  
  - `matplotlib.pyplot` (imported as `plt`)  
  - `scikit-learn` (`from sklearn.datasets import load_iris`)

> Replace “3.x” and add exact version numbers (e.g., `pandas 2.1.0`, `scikit-learn 1.3.1`) based on `pip list` or `conda list` from the environment where you ran the notebook.

## Data Loading and Structure

- The Iris dataset is loaded using `load_iris()` from `sklearn.datasets` and then converted into a `pandas` DataFrame with four feature columns: sepal length, sepal width, petal length, and petal width (all in centimeters).
- The dataset contains **150 rows and 4 numerical feature columns**, with no missing values; all columns are of `float64` type, and basic inspection with `head()`, `tail()`, `info()`, and `describe()` confirms the dataset is clean and ready for analysis.

## Key Findings from Data Exploration

- Descriptive statistics show that petal measurements (length and width) have larger standard deviations and wider ranges than sepal measurements, indicating that petals vary more across observations than sepals.
- The minimum and maximum values reveal that petal length spans from about 1.0 to 6.9 cm and petal width from about 0.1 to 2.5 cm, while sepal features occupy a narrower relative range; this suggests petal features are more informative for distinguishing different flower types.
- Quartile values (25%, 50%, 75%) show a strong shift in petal length and width between lower and upper quantiles compared with more modest shifts in sepal measurements, reinforcing that petal measurements carry stronger separation signal between groups than sepal measurements in this dataset.


*Livan Hagi Osman*
