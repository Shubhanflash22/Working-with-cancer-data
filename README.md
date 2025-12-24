# Cancer Prediction Using Machine Learning 🧬💻

A machine learning project that predicts whether a patient has cancer or not based on patient data and feature variables.

## Table of Contents

* [Project Overview](#project-overview)
* [Dataset](#dataset)
* [Features](#features)
* [Installation](#installation)
* [Usage](#usage)
* [Models](#models)
* [Results](#results)
* [Future Work](#future-work)
* [License](#license)

## Project Overview

This project aggregates patient data to predict the presence of cancer using machine learning models. Starting with a baseline logistic regression model, various classifiers were explored and hyperparameters tuned to improve accuracy. Please note that the data used in this exercize is completely fake.

Key components include:

* Data aggregation and preprocessing for multiple patient datasets.
* Feature analysis and baseline model creation.
* Exploration of multiple classifiers for optimal prediction accuracy.

## Dataset

* Patient data with over 30 feature variables per patient.
* Includes demographic, medical, and diagnostic features.
* Preprocessed to remove missing values, normalize features, and prepare for modeling.

## Features

* **Cancer Prediction:** Predicts whether a patient has cancer or not.
* **Feature Analysis:** Helps identify important variables contributing to prediction.
* **Model Comparison:** Baseline logistic regression compared with Decision Trees, Naïve Bayes, and SVM.
* **Hyperparameter Tuning:** Improves model accuracy and generalization.

## Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/Working-with-cancer-data.git
cd Working-with-cancer-data

# Pip install required Python packages
```

## Usage

1. Prepare patient dataset in CSV format.
2. Run the EDA script to understand the data

```bash
python SHUBHAN MITAL - ML-A2-Cancer Activity.ipynb
```
3. Run the prediction script:

```bash
python SHUBHAN MITAL - Assignment_2_EDA.ipynb
```
## Models

* **Logistic Regression:** Baseline model for initial comparison.
* **Decision Tree Classifier:** Explored for non-linear patterns.
* **Naïve Bayes Classifiers:** Tested for probabilistic predictions.
* **Support Vector Machine (SVM):** Selected as the most accurate model with hyperparameter tuning.

## Results

* SVM achieved prediction accuracy above 99%.
* Baseline and other models provided benchmarks for comparison.
* Demonstrated reliable performance on real-world patient datasets.

## Future Work

* Include more diverse patient datasets to improve generalization.
* Explore ensemble methods (Random Forest, Gradient Boosting) for further improvement.
* Deploy as a clinical decision support tool for early cancer detection.

## Citation

If you use this work, please cite:

```bibtex
@software{Working-with-cancer-data,
  author = {Shubhan Mital},
  title = {Working with cancer data},
  year = {2025},
  url = https://github.com/Shubhanflash22/Working-with-cancer-data.git
}
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
