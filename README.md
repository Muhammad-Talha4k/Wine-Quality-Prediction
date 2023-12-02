# Wine Quality Prediction using Xgboost Classifier

This project aims to predict the quality of red wine using Xgboost Classifier based on various physicochemical properties such as acidity, alcohol, sulphates, etc. The dataset used for this project is the [Wine Quality dataset], which contains 1599 records of red wine samples, with 11 input features and 1 output variable that ranges from 0 (very bad) to 10 (very good).

## Installation and Usage

To run this project, you will need the following libraries:

- pandas
- numpy
- xgboost
- sklearn
- matplotlib
- seaborn

You can install them using pip:

```bash
pip install pandas numpy xgboost sklearn matplotlib seaborn
```
To run the project, you can use the following command:

1. After installing the dependencies, you can clone this repository to your local machine using the following command:
   ```bash
   git clone https://github.com/Muhammad-Talha4k/Wine-Quality-Prediction.git

This notebook contain the code and explanation of the task.

## Results

The XGBoost model achieved an accuracy of 94% on the test set.

The model was able to predict the wine quality really well because of the label encoding of the target variable, for quality value greater than or equal to 7 its a good quality wine else its a bad quality wine. From Correlation heatmap We can see "alcohol" column is highly positive correlated with the "quality" column and "volatile acidity" has high negative correlation with the "quality" column.

## Contributions

We welcome contributions from the community. Feel free to suggest improvements, fixes, or new features through issues or pull requests.