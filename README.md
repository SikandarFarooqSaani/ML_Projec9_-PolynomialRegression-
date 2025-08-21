# Polynomial Regression Example 🚀

This project shows how **polynomial regression** can perform better than simple linear regression when data has a curved relationship.

## 📂 Dataset
- Source: [Kaggle - Polynomial Regression Dataset](https://www.kaggle.com/datasets/mirajdeepbhandari/polynomial-regression)

## 📌 Steps in the Project
1. **Imported libraries**:  
   `numpy`, `pandas`, `matplotlib`, `sklearn`, `kagglehub`, `os`

2. **Data Cleaning**:  
   - Checked for null values  
   - Checked for duplicates  
   - Checked data types  

3. **Data Visualization**:  
   - Plotted the data  
   - Found that there is **1 feature and 1 target**  
   - Relationship looked **parabolic (curve-shaped)**  

## 🔎 Linear Regression Attempt
- Split data into train and test sets  
- Trained a **Simple Linear Regression** model  
- **R² Score:** `-0.13` (worse than the mean line 😅)  
- The line was straight, touching some points but missing most others  

## 🔄 Polynomial Regression Attempt
- Created **Polynomial Features (degree = 2)**  
- Transformed training and testing sets  
- Trained the regression model again  
- **R² Score:** `0.91` 🎉  
- Plotted the curve → much better fit!  

## ✅ Conclusion
- Linear regression didn’t work well because the data was curved  
- Polynomial regression (degree 2) gave a great fit with an R² score of **0.91**  
- This shows why choosing the right model matters!  

---
💡 This project is a simple example for learning regression techniques.
