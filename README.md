
# Machine Learning Project: Loan Default Prediction

## Project Overview
This project focuses on predicting loan defaults using data from a German bank. The dataset, named "credit.csv", contains 1000 rows and 17 columns, with each row representing a customer. The goal is to apply machine learning techniques to accurately predict loan defaults, enhancing decision-making processes for financial institutions.

## Repository Structure
- `data/`: Contains the raw dataset and any processed data files.
- `scripts/`: Python scripts for data preprocessing, manipulation, visualization, and running machine learning models.
- `notebooks/`: Jupyter notebooks for exploratory data analysis and model evaluation.
- `results/`: Generated reports, figures, and tables that provide insights and model performance evaluations.

## Python Code Documentation
### Data Handling
Python scripts in `scripts/data_handling.py` are responsible for:
- Reading the dataset from the `data/` directory.
- Exploring and cleaning the dataset using automated scripts, ensuring no manual edits on raw data.

### Data Manipulation and Visualization
Python scripts in `scripts/data_manipulation.py` include functions for:
- Manipulating and wrangling the data to prepare it for modeling.
- Visualizing different aspects of the data using libraries like matplotlib and seaborn to create insightful plots.

### Machine Learning Models
Python scripts in `scripts/modeling.py` cover:
- The implementation of various machine learning models to predict loan defaults.
- The creation of publication-worthy figures and tables to demonstrate model performance.

## Running the Project
To run this project, navigate to the root directory and execute the following command:
```bash
python main.py
```
Ensure all dependencies are installed by running:
```bash
pip install -r requirements.txt
```

## Conclusion
This project provides a comprehensive analysis and application of machine learning techniques to predict loan defaults, which can significantly aid financial institutions in risk management.
