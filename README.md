# Decision Tree Models with Scikit-Learn

This repository contains implementations and experiments involving Decision Tree models using the [Scikit-Learn](https://scikit-learn.org/) library. The notebooks demonstrate classification, regression, and domain-specific use cases (e.g., heart disease prediction).

## Contents

### 1. `decision_tree_classifier.ipynb`

- **Purpose**: Implements a Decision Tree Classifier on a standard classification dataset.
- **Key Features**:
  - Data preprocessing and visualization
  - Model training and evaluation (accuracy, confusion matrix)
  - Decision tree visualization using `plot_tree`
- **Use Case**: Binary or multiclass classification tasks.

### 2. `decision_tree_regressor.ipynb`

- **Purpose**: Implements a Decision Tree Regressor for predicting continuous values.
- **Key Features**:
  - Uses datasets like Boston Housing (or similar)
  - Evaluates model with metrics like MSE and R²
  - Visual analysis of predictions vs actual values
- **Use Case**: Regression problems in housing, finance, etc.

### 3. `heart_decision_tree.ipynb`

- **Purpose**: Applies a Decision Tree Classifier to a heart disease dataset.
- **Key Features**:
  - Focus on medical data preprocessing
  - Performance evaluation (confusion matrix, classification report)
  - Tree depth and feature importance analysis
- **Use Case**: Medical diagnostics and binary classification.

## Dataset Used

The `heart_decision_tree.ipynb` notebook uses a dataset named **`heart.csv`**, which contains 1,025 records and 14 features relevant to heart disease prediction.

### Feature Descriptions

| Feature     | Description |
|-------------|-------------|
| `age`       | Age of the patient (in years) |
| `sex`       | Sex (1 = male; 0 = female) |
| `cp`        | Chest pain type (0 = typical angina, 1 = atypical angina, 2 = non-anginal pain, 3 = asymptomatic) |
| `trestbps`  | Resting blood pressure (in mm Hg) |
| `chol`      | Serum cholesterol level (in mg/dl) |
| `fbs`       | Fasting blood sugar > 120 mg/dl (1 = true; 0 = false) |
| `restecg`   | Resting electrocardiographic results (0 = normal, 1 = ST-T wave abnormality, 2 = left ventricular hypertrophy) |
| `thalach`   | Maximum heart rate achieved |
| `exang`     | Exercise-induced angina (1 = yes; 0 = no) |
| `oldpeak`   | ST depression induced by exercise relative to rest |
| `slope`     | Slope of the peak exercise ST segment (0 = upsloping, 1 = flat, 2 = downsloping) |
| `ca`        | Number of major vessels (0–3) colored by fluoroscopy |
| `thal`      | Thalassemia (1 = normal, 2 = fixed defect, 3 = reversible defect) |
| `target`    | Target variable (1 = heart disease; 0 = no heart disease) |

Ensure the `heart.csv` file is located in the root directory for proper notebook execution.

## Project Structure

```
decision-tree-models/
│
├── heart.csv                          # Dataset used for heart disease prediction
├── decision_tree_classifier.ipynb     # Decision Tree Classifier demo
├── decision_tree_regressor.ipynb      # Decision Tree Regressor demo
├── heart_decision_tree.ipynb          # Heart disease classification
└── README.md                          # Project documentation
```
