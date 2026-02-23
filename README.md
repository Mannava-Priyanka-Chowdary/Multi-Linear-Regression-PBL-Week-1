# 📊 Multi Linear Regression – 50 Startups Dataset (PBL-Week1)

## 📌 Project Overview
This project demonstrates the implementation of **Multiple Linear Regression** using the 50 Startups dataset.  
The goal is to predict the **Profit** of a startup based on:

- R&D Spend
- Administration
- Marketing Spend
- State

This project was developed as part of PBL (Project-Based Learning) – Week 1.



## 📂 Dataset Information

The dataset contains 50 observations with the following features:

| Feature | Description |
|----------|-------------|
| R&D Spend | Amount spent on research and development |
| Administration | Administrative costs |
| Marketing Spend | Marketing budget |
| State | Location of the startup |
| Profit | Target variable (dependent variable) |

There are no missing values in the dataset.



## 🛠 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook



## 🔍 Steps Performed

1. Import required libraries  
2. Load the dataset  
3. Perform exploratory data analysis (EDA)  
4. Handle categorical variable (State)  
5. Split data into training and testing sets  
6. Train the Multiple Linear Regression model  
7. Evaluate the model using R² score  
8. (Optional) Apply Lasso Regression for comparison  



## 🤖 Model Used

### Multiple Linear Regression

The model predicts profit using the formula:

Profit = β₀ + β₁(R&D Spend) + β₂(Administration) + β₃(Marketing Spend) + β₄(State)

Where:
- β₀ = Intercept
- β₁, β₂, β₃, β₄ = Coefficients



## 📈 Results

- The model was evaluated using **R² Score**
- The model shows strong prediction performance
- R&D Spend has the highest impact on Profit



## ▶️ How to Run This Project

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Multi-Linear-Regression-PBL-Week-1-.git
