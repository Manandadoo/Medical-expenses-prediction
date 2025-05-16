# Medical Expenses Prediction

## 📋 Project Overview

This project aims to predict individual medical insurance expenses using machine learning. By analyzing features such as age, gender, BMI, number of children, smoking status, and region, the model estimates the cost of medical charges billed by health insurance. This serves as a practical demonstration of regression techniques applied to real-world data.

## 🧰 Technologies and Tools

- Python 3.x  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Jupyter Notebook  

## 🔍 Dataset

The dataset includes the following columns:

- `age`: Age of the insured individual  
- `sex`: Gender  
- `bmi`: Body Mass Index  
- `children`: Number of dependents  
- `smoker`: Smoking status (yes/no)  
- `region`: Residential region in the US  
- `charges`: Medical insurance charges (target variable)

This dataset is often used in regression modeling tutorials and reflects realistic health-related cost factors.

## 🛠️ Project Workflow

- Loaded and explored the dataset  
- Performed data cleaning and preprocessing  
- Conducted exploratory data analysis (EDA) using visualizations  
- Encoded categorical variables for modeling  
- Trained a Linear Regression model to predict medical charges  
- Evaluated the model using MAE and R² score  

## 📈 Results

The model shows that smoking status, age, and BMI are strong predictors of medical charges. The trained regression model achieved reasonable accuracy, making it useful for basic cost estimation.

## 🚀 Getting Started

To run this project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/medical-expenses-prediction.git
   cd medical-expenses-prediction
   ```

2. Install required packages (optional):
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

3. Launch the notebook:
   ```bash
   jupyter notebook medical-expenses-prediction.ipynb
   ```