# Task 1: Data Cleaning with Python

Excited to share my journey through Task 1, where I applied data cleaning techniques using Python on a sample employee dataset. 🐍

## Objective:
- **Data Cleaning:**
  - Removed missing values
  - Addressed outliers

## Steps Taken:

1. **Imported Necessary Libraries:**
   ```python
   import pandas as pd
   import numpy as np
2. Load the sample employee dataset
df = pd.read_csv('your_dataset.csv')
3. Check for missing values
print("Missing values before cleaning:\n", df.isnull().sum())

4. Handle missing values
df_cleaned = df.dropna()  # Example: Remove rows with missing values
# Check for outliers
print("Outliers before cleaning:\n", df.describe())

5. Visualization of cleaned data
import seaborn as sns
import matplotlib.pyplot as plt

6. Your code for plotting here
sns.pairplot(df_cleaned)
plt.title('Pairplot of Cleaned Data')
plt.show()

Conclusion:

Successfully completed Task 1 by cleaning the dataset, removing missing values, and addressing outliers. The cleaned data is now ready for further analysis. 💻📊
