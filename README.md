# 🔥 Energy Efficiency Prediction using PCA & Machine Learning

This repository focuses on predicting building heating load by applying Principal Component Analysis (PCA) for dimensionality reduction and training a regression model for accurate energy load forecasting.

Machine learning helps reduce energy consumption by analyzing structural features of buildings and forecasting the required heating load efficiently.

---

## 📌 Project Objectives

• Perform PCA to remove redundant features  
• Improve model performance with transformed principal components  
• Build a regression model *(Linear Regression/Random Forest)*  
• Visualize variance explained & model evaluation metrics  

---

## 🧠 Methodology

1️⃣ Import and clean the dataset  
2️⃣ Standardize feature variables  
3️⃣ Apply PCA to extract principal components  
4️⃣ Train the regression model  
5️⃣ Evaluate the model using MSE and R² score  
6️⃣ Visualize results with plots  

---

## 📊 Dataset

• Source: UCI Machine Learning Repository  
• Energy Efficiency dataset  
• Contains thermal properties of buildings and load output values  

---

## 🔎 Technologies Used

• Python  
• NumPy  
• Pandas  
• Matplotlib  
• Scikit-Learn  

---

## 🚀 Results

PCA successfully reduced dataset dimensionality while maintaining high model accuracy.  
Regression on principal components improved efficiency and reduced computation time.

---

## 💡 Applications

This model can help in  
• Smart building automation  
• Sustainable energy development  
• Cost-effective architectural decision-making  
• Real-time energy demand forecasting  
• Government green standards evaluation  

---

## 📁 Repository Contents

| Folder | Description |
|--------|-------------|
| data | Dataset used for training |
| src | Model training source code |
| outputs | Visual graphs & results screenshots |
| notebooks | End-to-end Jupyter Notebook |

---

## ✅ Conclusion

PCA enhances the accuracy and performance of machine learning models by minimizing redundant data and providing efficient, optimized inputs for energy prediction systems. This project demonstrates that PCA is a powerful tool in real-time energy management.

---

## 📌 How to Run

```bash
pip install -r requirements.txt
python src/model.py
