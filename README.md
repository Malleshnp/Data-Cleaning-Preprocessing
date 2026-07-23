# Task 1: Data Cleaning & Preprocessing

## AI & ML Internship

### Objective
The objective of this task is to clean and preprocess raw data to prepare it for machine learning models. This project uses the Titanic dataset and demonstrates essential preprocessing techniques.

---

## Dataset

- **Dataset:** Titanic Dataset
- **Source:** Kaggle
- **Downloaded using:** KaggleHub

---

## Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- KaggleHub

---

## Project Workflow

### 1. Download Dataset
- Downloaded the Titanic dataset using KaggleHub.

### 2. Explore the Dataset
- Displayed the first five rows.
- Checked dataset dimensions.
- Inspected data types.
- Identified missing values.
- Generated descriptive statistics.

### 3. Handle Missing Values
- Filled missing values in the **Age** column using the median.
- Filled missing values in the **Embarked** column using the mode.
- Dropped the **Cabin** column due to a large number of missing values.

### 4. Encode Categorical Variables
- Converted categorical columns (**Sex** and **Embarked**) into numerical values using Label Encoding.

### 5. Remove Unnecessary Columns
Dropped columns that are not useful for model training:
- PassengerId
- Name
- Ticket

### 6. Feature Scaling
Applied **StandardScaler** to standardize numerical features:
- Age
- Fare

### 7. Detect Outliers
Visualized outliers using boxplots for:
- Age
- Fare

### 8. Remove Outliers
Used the **Interquartile Range (IQR)** method to remove extreme values from the Fare column.

### 9. Save Cleaned Dataset
Saved the processed dataset as:

```
Titanic_Cleaned.csv
```

---

## Project Structure

```
Task-1-Data-Cleaning/
│
├── task1_preprocessing.py
├── Titanic_Cleaned.csv
├── README.md
├── requirements.txt
└── screenshots/
```

---

## Requirements

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn kagglehub
```

---

## Results

- Successfully cleaned the dataset.
- Handled missing values.
- Encoded categorical variables.
- Standardized numerical features.
- Visualized and removed outliers.
- Saved the cleaned dataset for future machine learning tasks.

---

## Author

**Your Name**