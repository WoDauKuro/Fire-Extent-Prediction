# Predict Fire Area

This project uses machine learning to predict burn areas based on various environmental factors. It utilizes LightGBM, a gradient boosting framework, along with grid search for hyperparameter tuning to create an accurate prediction model.

## Table of Contents

- [Project Overview](#project-overview)
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Model](#model)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The goal of this project is to predict the burn area of fires using environmental data. We use a LightGBM regressor and perform hyperparameter tuning using GridSearchCV to optimize the model's performance.

## Installation

To run this project, you need Python 3.7+ and the following libraries:

```
pip install pandas numpy matplotlib seaborn scikit-learn lightgbm
```

## Usage

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/predict-fire.git
   cd predict-fire
   ```

2. Run the Jupyter notebook:
   ```
   jupyter notebook predict-fire-notebook.ipynb
   ```

3. Follow the steps in the notebook to load the data, preprocess it, train the model, and make predictions.

## Data

The project uses two datasets:

- `Train.csv`: Used for training and validating the model
- `Test.csv`: Used for making final predictions

The data includes various environmental factors and a target variable 'burn_area'.

## Model

We use LightGBM, a gradient boosting framework that uses tree-based learning algorithms. The model is optimized using GridSearchCV to find the best hyperparameters.

Key features of the model:

- Hyperparameter tuning using GridSearchCV
- Cross-validation for robust performance estimation
- Feature importance analysis

## Results

The model's performance is evaluated using Root Mean Squared Error (RMSE). The notebook includes visualizations of feature importances to provide insights into the most influential factors in predicting burn areas.

## Contributing

Contributions to this project are welcome! Please fork the repository and submit a pull request with your proposed changes.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

