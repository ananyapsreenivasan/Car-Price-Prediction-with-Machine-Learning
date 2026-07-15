# Car-Price-Prediction-with-Machine-Learning

##  Project Overview

This project predicts the selling price of used cars using Machine Learning regression algorithms. It involves data preprocessing, exploratory data analysis (EDA), feature engineering, model building, and performance evaluation.

The project compares multiple regression models to identify the best-performing algorithm for predicting car prices.

---

##  Dataset

**Dataset:** Car Details from CarDekho

The dataset contains information about used cars, including:

- Car Name
- Year of Manufacture
- Selling Price (Target Variable)
- Kilometers Driven
- Fuel Type
- Seller Type
- Transmission
- Owner Type

---

##  Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

##  Project Workflow

### 1. Data Loading
- Imported the dataset using Pandas.
- Displayed dataset information and statistics.

### 2. Data Cleaning
- Checked for missing values.
- Removed duplicate records.
- Standardized categorical values.

### 3. Feature Engineering
- Created a new feature:
  - **Car Age = Current Year − Manufacturing Year**
- Extracted the **Brand** name from the car name.
- Removed unnecessary columns:
  - Name
  - Year

### 4. Exploratory Data Analysis (EDA)

Visualizations include:

- Distribution of Selling Price
- Selling Price by Fuel Type
- Selling Price vs Car Age

---

##  Machine Learning Models

The following regression models were implemented:

- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor

A preprocessing pipeline was created using:

- One-Hot Encoding for categorical variables
- ColumnTransformer
- Pipeline

---

##  Model Evaluation

The models were evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

Finally, the performance of all models was compared in a summary table.

---

##  Project Structure

```
Car-Price-Prediction/
│
├── Car_Price_Prediction.ipynb
├── README.md
└── dataset.csv
```

---

##  How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/Car-Price-Prediction.git
```

2. Navigate to the project folder

```bash
cd Car-Price-Prediction
```

3. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

4. Open the notebook

```bash
jupyter notebook Car_Price_Prediction.ipynb
```

---

##  Key Features

- Data preprocessing and cleaning
- Feature engineering
- Exploratory Data Analysis
- Machine Learning model comparison
- Performance evaluation using multiple metrics
- End-to-end regression pipeline

---
 
## visualizations

The notebook includes:

- Selling Price Distribution
- Fuel Type vs Selling Price
- Car Age vs Selling Price

---

##  Future Improvements

- Hyperparameter tuning
- Cross-validation
- XGBoost and LightGBM models
- Model deployment using Flask or Streamlit
- Interactive web application

---

##  Author

**Ananya P. Sreenivasan**

B.Sc. Physics, Mathematics & Computer Science  
Amrita Vishwa Vidyapeetham, Mysuru

---

## ⭐ If you found this project useful, consider giving it a star!
