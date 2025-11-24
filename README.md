# Pandas Basics

A beginner-friendly Jupyter notebook demonstrating essential Pandas operations for data manipulation and analysis.

## Overview

This tutorial uses the Titanic dataset to showcase common Pandas operations that every data analyst should know.

## Prerequisites

```bash
pip install pandas jupyter
```

## Dataset

- **File**: `titanic.csv`
- **Source**: Titanic passenger data
- **Columns**: PassengerId, Survived, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, Embarked

## Topics Covered

### 1. Data Loading
- Reading CSV files with `pd.read_csv()`

### 2. Data Exploration
- `df.describe()` - Statistical summary
- `df.shape` - Dimensions of the dataset
- `df.head()` - First 5 rows
- `df.tail()` - Last 5 rows
- `df.sample()` - Random sampling with fixed seed

### 3. Data Access & Modification
- `df.loc[]` - Label-based indexing
- Updating specific cells

### 4. Data Filtering
- Boolean indexing with single condition: `df[df["Age"] > 25]`
- Multiple conditions with `&` operator
- Column selection from filtered data

### 5. Data Information
- `df.info()` - Data types and missing values
- `df.drop()` - Removing columns

## Usage

1. Ensure `titanic.csv` is in the same directory
2. Open the notebook:
```bash
jupyter notebook pandas-tutorial.ipynb
```
3. Run cells sequentially to see each operation in action

## Key Concepts

- **DataFrame**: 2D labeled data structure
- **loc[]**: Access rows/columns by label
- **Boolean Indexing**: Filter data using conditions
- **Method Chaining**: Combine multiple operations

## Next Steps

- Learn `iloc[]` for position-based indexing
- Explore `groupby()` for aggregations
- Practice `merge()` and `join()` operations
- Study handling missing data with `fillna()` and `dropna()`

## License

MIT License - Feel free to use for learning purposes
