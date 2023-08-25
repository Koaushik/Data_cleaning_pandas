# Data_cleaning_pandas
From handling missing values to deduplicating entries, this repository aims to help users enhance their data preprocessing skills using Pandas.

## Data Cleaning in Pandas

This repository contains a Jupyter Notebook (`data_cleaning.ipynb`) that demonstrates various data cleaning techniques using the Pandas library in Python. The dataset used for this demonstration is `customer_call_list.xlsx`.

### Cleaning Steps

In the Jupyter Notebook, we perform the following data cleaning tasks using Pandas:

- **Loading the Data:** We start by loading the `customer_call_list.xlsx` dataset into a Pandas DataFrame.
- **Handling Missing Values:**
  - Identify and handle any missing values in the dataset using functions like `isna()`, `fillna()`, and `dropna()`.
- **Removing Duplicates:**
  - Identify and remove duplicate entries using the `duplicated()` and `drop_duplicates()` functions.
- **Data Transformation:**
  - Perform transformations such as changing data types, renaming columns, and applying functions using Pandas operations.
- **Dealing with Outliers:**
  - Detect and address outliers in numeric data columns through methods like z-scores or IQR (Interquartile Range).
- **Data Quality Checks:**
  - Conduct data quality checks to ensure consistency and accuracy after cleaning.

### How to Use the Notebook

1. Clone this repository to your local machine using:
   ```
   git clone https://github.com/your-username/data-cleaning-pandas.git
   ```
   
2. Open the `data_cleaning.ipynb` notebook in Jupyter Notebook or JupyterLab.
3. Run each cell in the notebook to see the step-by-step data cleaning process.

Feel free to explore, modify, and adapt the code to suit your specific data cleaning needs. Happy data cleaning!

For detailed code examples and explanations, please refer to the `data_cleaning.ipynb` notebook in this repository.

**Note:** Make sure you have Pandas and Jupyter Notebook installed in your environment to run the notebook successfully. You can install them using the following commands:
```bash
pip install pandas
pip install jupyter
```

For any questions or improvements, please feel free to open an issue or submit a pull request. Your contributions are highly appreciated.
