# Car Price Prediction and Vehicle Clustering

## Project Overview

This project applies Machine Learning techniques to analyze a used car dataset.

The project consists of two main tasks:

1. **Random Forest Regressor**
   - Predict vehicle prices using a Random Forest Regressor.

2. **Clustering**
   - Group similar vehicles using the K-Means clustering algorithm.

The project also includes data cleaning, preprocessing, feature engineering, model evaluation, and data visualization.

---

## Dataset

The dataset contains information about used cars, including:

- Price
- Mileage
- Engine Volume
- Manufacturer
- Model
- Fuel Type
- Production Year
- Gear Box Type
- Color
- Airbags
- And other vehicle features

---

## Data Preprocessing

The following preprocessing steps were performed:

- Removed duplicate records
- Handled missing values
- Removed price outliers using the IQR method
- Removed unrealistic mileage values
- Selected relevant features
- Applied StandardScaler for numerical features
- Applied OneHotEncoder for categorical features using ColumnTransformer

---

## Machine Learning Models

### Regression

- Random Forest Regressor

Evaluation Metrics:

- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

### Clustering

- K-Means Clustering
- StandardScaler
- Elbow Method for selecting the optimal number of clusters

Selected Features:

- Mileage
- Engine Volume
- Price

---

## Project Structure

```
Car-Price-Prediction/
│
├── car_price.csv
│
├── Week3_Project.ipynb
│
├── venv
│
└── README.md
```

---

## How to Run

### 1. Clone the repository

```bash
git clone <repository_link>
```

### 2. Install the required libraries

```bash
pip install pandas numpy matplotlib scikit-learn
```

### 3. Open the notebook

```bash
jupyter notebook
```

Open:

```
Week3_Project.ipynb
```

and run all cells in order.

---

## Results

### Random Forest Regression

- MSE: **31,561,178.42**
- RMSE: **5,617.93**
- R² Score: **0.75**

### K-Means Clustering

- Elbow Method selected **4 clusters**
- Vehicles were grouped based on:
  - Mileage
  - Engine Volume
  - Price

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## Author

**Muhammad Zaid Akram**

BS Computer Science