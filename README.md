# Breast Cancer Prediction Project

This project is an interactive and dynamic breast cancer classifier built with Python, pandas, scikit-learn, and visualization libraries. It walks through a machine learning pipeline for classifying tumors as benign or malignant using logistic regression and random forest models.

## Features

- Data cleaning and preprocessing (removal of null columns, encoding, scaling)
- Exploratory data analysis and visualization
- Model training and tuning (Logistic Regression, Random Forest)
- Dynamic calculation and display of accuracy scores
- Easily pluggable with new data for instant prediction and retraining

---

## Quick Start

1. **Clone the repo and install dependencies:**
    ```bash
    git clone https://github.com/Pratham-r05/Project_3.git
    cd Project_3
    pip install -r requirements.txt
    ```
2. **Launch the notebook:**
    ```bash
    jupyter notebook BreastCancer.ipynb
    ```

---

## Data Overview

- The dataset consists of 569 samples and 32 features after cleaning.
- The `diagnosis` column is mapped to 1 (Malignant) and 0 (Benign).
- Class distribution:
    - Benign (0): 357
    - Malignant (1): 212

---

## Interactive Exploration

You can interactively explore the data and visualize distributions using built-in code cells. Modify and run any cell to update the charts and tables on your data.

Example: To check the shape and columns of your DataFrame:
```python
print(df.shape)
print(df.columns)
```

---

## Dynamic Model Training

You can dynamically retrain models or adjust hyperparameters within the notebook. Example cells show how to split data, scale features, and run classifiers.

---

## Accuracy Score

The model accuracy score is dynamically computed in the notebook. After running the model training cells, you will see output like:
```
accuracy_score(y_test, y_pred)
```
Replace or extend this section with your actual accuracy (e.g., `Accuracy: 0.96`) once you run the cell on your data.

---

## Extending the Notebook

- Add more models by importing from `sklearn`.
- Upload new data using pandas and rerun the notebook for updated results.
- Use `GridSearchCV` for hyperparameter tuning interactively.

---

## Contributing

Feel free to fork and contribute! Open issues for bugs or feature requests.

---

## License

[MIT License](LICENSE)

---

*Interactive and dynamic: Edit, rerun, and experiment directly in the Jupyter notebook for real-time feedback and learning!*
