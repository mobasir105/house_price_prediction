

---

# House Price Prediction

This repository contains a Jupyter Notebook for predicting house prices using various machine learning models. The notebook demonstrates data loading, cleaning, feature engineering, and model training and evaluation.

## Dataset

The dataset used in this project is `home_data.csv`, which contains various features of houses such as price, number of bedrooms, bathrooms, square footage, and more.

## Project Structure

- **Data Loading:** The dataset is loaded using pandas.
- **Data Cleaning:** Unnecessary columns are dropped, and data types are converted as needed.
- **Feature Engineering:**
  - Converting `yr_built` to `age`
  - Converting `yr_renovated` to a binary `renovated` column
  - Applying feature scaling
- **Models Used:**
  - Linear Regression
  - Polynomial Regression
  - Decision Trees
  - Ridge Regression
- **Evaluation Metrics:**
  - Mean Squared Error (MSE)
  - R-squared (R²)
  - Mean Absolute Error (MAE)

## Dependencies

The project requires the following Python libraries:

- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn

You can install these dependencies using the following command:

```sh
pip install numpy pandas matplotlib seaborn scikit-learn
```

## Usage

To run the notebook, simply open it in Jupyter Notebook or JupyterLab and execute the cells. The notebook will guide you through the steps of data cleaning, feature engineering, model training, and evaluation.

## Results

The notebook provides a comprehensive analysis of the dataset and evaluates the performance of different models. The results include visualizations and metrics to compare the models' effectiveness in predicting house prices.

## License

This project is licensed under the MIT License.

---

