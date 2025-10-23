# 🎯 What I Aimed For.
---

The project aims to build and train a machine learning model to estimate the energy consumed by different 5G base stations. This will take into account various engineering configurations, traffic conditions, and energy-saving methods.

This project is a checkpoint for the '5G-Energy consumption' dataset provided by the International Telecommunication Union (ITU) in 2023 as part of a global challenge for data scientists.

# ℹ️ Instructions.
---

## Data Handling:

- Import Data and Perform Basic Exploration: Import the dataset and explore its basic structure and statistics.

- Display General Information: Display basic information and summary statistics about the dataset.

- Create a Pandas Profiling Report: Generate a pandas profiling report to gain insights into the dataset.

- Handle Missing and Corrupted Values: Address any missing or corrupted values in the dataset.

- Remove Duplicates: Remove any duplicate records if they exist.

- Handle Outliers: Detect and handle any outliers in the dataset.

- Encode Categorical Features: Encode categorical features to prepare them for machine learning algorithms.

- Select Target Variable and Features: Select the target variable (Energy) and the feature set.

- Split Dataset: Split the dataset into training and test sets.


## Model Building and Evaluation:

- Select ML Regression Algorithm: Based on the data exploration phase, select a suitable ML regression algorithm.

- Train the Model: Train the model on the training set.

- Assess Model Performance: Evaluate the model performance on the test set using relevant evaluation metrics.


# 🛠️ Tools Used.
---

- VSCode: Code editor.
- GitHub: Repository hosting.
- Git: Version control.
- Python: Programming language.
- Google: For research and troubleshooting.
- YouTube: For educational videos.

```
#Libraries for data manipulation and visuallization
import pandas as pd
import numpy as np
from ydata_profiling import ProfileReport

#Libraries for preprocessing
from sklearn.preprocessing import LabelEncoder
from sklearn.model_selection import train_test_split

#Libraries for models
from sklearn.linear_model import LinearRegression
from sklearn.ensemble import RandomForestRegressor

#Libraries for evaluation
from sklearn.metrics import mean_absolute_error, mean_squared_error
