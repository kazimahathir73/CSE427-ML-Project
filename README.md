# Stock Prediction Project

Welcome to the Stock Prediction Project repository! This project utilizes machine learning models, including Random Forest, Logistic Regression, and Support Vector Machines (SVM), to predict stock prices based on historical data. The dataset used for this project is the S&P 300 index.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Models Used](#models-used)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)

## Project Overview

This project aims to predict stock prices using machine learning models. Predicting stock prices is a challenging task, and this project serves as an example of how various models can be applied to solve real-world problems. The project includes the following components:

- Data collection and preprocessing
- Feature engineering
- Model training and evaluation
- Visualization of results

## Dataset

We used historical data from the S&P 300 index for training and testing our models. The dataset includes various attributes such as date, open price, close price, volume, and more. This data was obtained using the `yfinance` Python library.

## Models Used

We employed the following machine learning models for stock price prediction:

1. Random Forest
2. Logistic Regression
3. Support Vector Machines (SVM)

Each model's performance was evaluated based on including accuracy score and F1 score.

## Usage

- The Jupyter Notebook `stock_prediction.ipynb` provides a step-by-step walkthrough of the entire project, from data loading to model evaluation.

- The Python scripts in the `scripts` directory can be run individually to perform specific tasks, such as data preprocessing or model training.

## Results

We achieved the following accuracy (F1 score) with our models:

- Random Forest: 0.5704697986577182
- SVM: 0.6486486486486487
- Logistic Regression: 0.6486486486486487

You can find more details on model performance in the project's Jupyter Notebook.

## Contributing

Contributions are welcome! If you'd like to contribute to this project or report issues, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your fork.
5. Open a pull request to the main repository.
