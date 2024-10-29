# Titanic---Machine-Learning-from-Disaster

## Titanic Survival Prediction

This project explores the Titanic dataset, performing data preprocessing, exploratory data analysis, feature engineering, and model building to predict passenger survival based on various features. Three models are trained and evaluated: Logistic Regression, Random Forest, and Gradient Boosting Classifier.

## Project Structure
- Data Loading and Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Building

## Installation
To run this project, install the following Python libraries:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## Usage

1. Clone this repository:

```bash
git clone https://github.com/yourusername/titanic-survival-prediction.git
```
2. Open notebook.ipynb in Jupyter Notebook or JupyterLab.
3. Run the cells sequentially to replicate the data analysis, model building, and evaluation steps.


## Results

## Results

| Model               | Accuracy | Confusion Matrix               |
|---------------------|----------|--------------------------------|
| Logistic Regression | 0.799    | \[\[85, 20\], \[16, 58\]\]     |
| Random Forest       | 0.844    | \[\[89, 16\], \[12, 62\]\]     |
| Gradient Boosting   | 0.844    | \[\[89, 16\], \[12, 62\]\]     |

- **Logistic Regression** achieved an accuracy of **79.9%**, indicating reasonable performance in classifying survival outcomes.
- **Random Forest** and **Gradient Boosting** both achieved **84.4%** accuracy, with slightly better handling of class imbalances as shown in their confusion matrices.

Overall, the **Random Forest** and **Gradient Boosting** models provide the best performance for predicting passenger survival on the Titanic.


## Acknowledgments

- Kaggle for providing the Titanic dataset.
- Scikit-Learn and Seaborn libraries for data processing and visualization.
