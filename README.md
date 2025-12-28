# Basic-Data-Preprocessing-Tool
This project provides a modular Python-based data preprocessing pipeline using **Pandas**.  
It is designed to clean large CSV datasets (such as COVID datasets) and prepare them for Machine Learning tasks.

---

##  Features

- Load CSV file from user-defined path
- Remove duplicate rows
- Drop columns with more than **70% missing values**
- Fill remaining missing values:
  - Numerical → Mean
  - Categorical → "Unknown"
- Remove columns with more than **70% zero values**
- Replace remaining zero values with column mean
- Save cleaned dataset as a CSV file

---

##  Technologies Used

- Python
- Pandas
