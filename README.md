
# Kaggle Competition Group Project

This project was developed as part of a group effort to participate in a Kaggle machine learning competition. The notebook demonstrates the process of data loading, preprocessing, model building, evaluation, and submission preparation for the selected competition.

## Project Overview

- **Platform:** Google Colab
- **Main Libraries Used:** pandas, numpy, seaborn, scikit-learn, XGBoost, TensorFlow/Keras, matplotlib
- **Models Explored:** Random Forest, XGBoost, Neural Networks (Keras)
- **Tasks:** Data preprocessing, feature engineering, model training and tuning, prediction generation for competition submission.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook / Google Colab
- Packages:
  - numpy
  - pandas
  - seaborn
  - matplotlib
  - scikit-learn
  - xgboost
  - tensorflow / keras

You can install the requirements using pip:
```bash
pip install numpy pandas seaborn matplotlib scikit-learn xgboost tensorflow
```

### Data

This notebook expects the following files (as provided by the Kaggle competition):
- `train.csv`
- `test.csv`
- `sample_submission.csv`

Update the file paths as necessary if you are running locally rather than on Colab/Google Drive.

## Running the Notebook

1. Open the notebook in [Google Colab](https://colab.research.google.com/) or Jupyter Notebook.
2. Mount your Google Drive (if using Colab) to access the dataset files.
3. Run all cells sequentially to perform:
    - Data import and exploration
    - Preprocessing and feature engineering
    - Model training and hyperparameter tuning
    - Generating predictions for submission

## Features

- **Data Imputation:** KNN imputation for missing values.
- **Feature Scaling:** StandardScaler is used.
- **Label Encoding:** For categorical variable transformation.
- **Model Selection:** Random Forest, XGBoost, and Keras Neural Networks, with GridSearchCV for hyperparameter tuning.
- **Callbacks:** Early stopping and learning rate scheduling for neural networks.
- **Visualization:** Data analysis and model performance visualization using seaborn and matplotlib.

## Output

- Final predictions are generated in the format required by the competition and saved as a CSV ready for submission.

## Authors

- Abdul Bari    22092619
- Faraz Ahmed   22093522
- Hamza Bashir Qureshi    22084845
- Muhammad Junaid Hashmi    22057665   
- Muhammad Azeem    22095075
- Muhammad Junaid Hashmi    22057665
- Rana Sana ULLAH Khan Essa khailvi    22066704

## Acknowledgments

- Kaggle for the dataset and competition platform.
- Open-source contributors for the libraries used.

---
