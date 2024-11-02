# Titanic Kaggle Project

This project predicts survival on the Titanic using machine learning techniques. The dataset, available on Kaggle, is ideal for classification practice and uses both numeric and categorical features.

## Libraries Used
- **Data Manipulation**: `pandas`, `numpy`
- **Data Visualization**: `seaborn`, `matplotlib`
- **Machine Learning**: 
  - Preprocessing: `sklearn.preprocessing`, `sklearn.impute`, `sklearn.compose`
  - Model Selection & Evaluation: `sklearn.model_selection`
  - Algorithms: `LogisticRegression`, `SVC`, `RandomForestClassifier`, `DecisionTreeClassifier`, `KNeighborsClassifier`, `GaussianNB`

## Installation

1. Install dependencies:
   ```
   pip install pandas numpy seaborn matplotlib scikit-learn
   ```

2. Download the Titanic dataset (`train.csv` and `test.csv`) from the [Kaggle competition page](https://www.kaggle.com/c/titanic).

## Workflow

1. **Data Analysis**: Explore data with Seaborn and Matplotlib.
2. **Data Preprocessing**:
   - Encode categorical variables with `OrdinalEncoder` and `OneHotEncoder`
   - Handle missing values with `SimpleImputer`
   - Scale features with `StandardScaler`
3. **Model Training and Selection**: Use `Pipeline` and `GridSearchCV` to train models and find optimal parameters.
4. **Evaluation**: Use cross-validation with `StratifiedKFold` and evaluate with metrics.

## Usage

1. Run the project notebook or script to preprocess data, train models, and generate predictions.
2. Submit predictions to Kaggle in the required format for evaluation.

## Files

- `titanic.ipynb`: Contains all code for data analysis, preprocessing, and model training.
- `train.csv` and `test.csv`: Training and test datasets from Kaggle.

## Resources
- [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic) for dataset details and submission guidelines.

```

This README covers setup, workflow, and usage details for your Titanic project using Scikit-learn tools and a range of classification algorithms.
