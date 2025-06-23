# AIML_Titanic_Task1
Data cleaning and preprocessing of the Titanic dataset as part of the AI &amp; ML Internship Task 1. Includes handling null values, encoding, feature scaling, and outlier removal using Python and Pandas.
# AIML Internship Task 1 - Titanic Data Preprocessing

📄 Files Included
- `Task1.ipynb` – Jupyter notebook for cleaning and preprocessing
- `Titanic-Dataset.xlsx` – Original dataset
- `titanic_cleaned.xlsx` – Final cleaned dataset

🔧 Tools Used
- Python
- Pandas, NumPy, Matplotlib
- scikit-learn

✅ Steps Performed
1. Loaded Titanic dataset
2. Handled missing values (`Age`, `Embarked`)
3. Dropped `Cabin` (too many nulls)
4. Encoded `Sex` and `Embarked` columns
5. Normalized `Age` and `Fare`
6. Removed outliers using IQR method
7. Saved cleaned dataset
