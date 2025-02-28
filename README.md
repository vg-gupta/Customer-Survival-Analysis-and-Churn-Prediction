# **Customer Survival Analysis & Churn Prediction** 📊🔍  

### **🚀 AI-Powered Predictive Analytics for Customer Retention**  


## **📌 Project Overview**  
Customer attrition, also known as **customer churn**, is a key business challenge for industries like **telecom, banking, SaaS, and subscription-based services**. This project implements a **Customer Survival Analysis & Churn Prediction** system using **Machine Learning (ML) & Deep Learning (DL)** to identify at-risk customers and predict when they might churn.  

By leveraging **Survival Analysis** and **Predictive Analytics**, this project helps businesses:  
✔️ Understand **why customers leave**  
✔️ Predict **which customers are at risk**  
✔️ Calculate **expected customer lifetime value (CLV)**  
✔️ Provide **data-driven retention strategies**  

## **🎯 Key Features**  
✅ **Customer Survival Analysis** using Kaplan-Meier curves, Log-Rank tests & Cox Proportional Hazard Models  
✅ **Churn Prediction Model** using Random Forest with Explainable AI (SHAP, Feature Importance, Partial Dependence Plots)  
✅ **Real-Time Prediction App** – Input customer data to get **churn probability & risk assessment**  
✅ **Customer Lifetime Value Estimation** – Predicts remaining lifetime & potential revenue loss  
✅ **Comprehensive Data Analysis** – Insights into **tenure, services, contracts, payment methods, & monthly charges**  
✅ **Explainability & Interpretability** – SHAP values, permutation importance, and model visualization  

---

## **🛠 Technologies & Tools**  
🔹 **Machine Learning & AI**: Random Forest, Cox-Proportional Hazard Model  
🔹 **Data Science & Analytics**: Pandas, NumPy, Matplotlib, Seaborn  
🔹 **Explainable AI (XAI)**: SHAP (Shapley Additive Explanations), Feature Importance, Partial Dependence Plots  
🔹 **Model Deployment**: Flask, Heroku, Scikit-learn, Pickle  
🔹 **Visualization & Reporting**: Kaplan-Meier Survival Curves, Hazard Curves, Decision Trees  

---

## **📊 Project Workflow**  
### **1️⃣ Data Preprocessing & Exploratory Analysis**  
- Clean & preprocess customer data  
- Analyze **customer behavior, churn trends, and survival probabilities**  
- Compute Kaplan-Meier survival estimates  

### **2️⃣ Survival Analysis & Hazard Prediction**  
- Perform **Log-Rank Tests** to compare churn rates across different groups  
- Fit **Cox-Proportional Hazard Models** to analyze churn risk factors  
- Generate **Survival & Hazard Curves** to visualize customer retention trends  

### **3️⃣ Churn Prediction Model (Random Forest)**  
- Train a **Random Forest model** for binary churn prediction  
- Handle **class imbalance** using weighted loss functions  
- Tune hyperparameters using **Grid Search Cross-Validation**  
- Evaluate model performance using **F1 Score, ROC-AUC, and Precision-Recall metrics**  

### **4️⃣ Explainability & Insights**  
- Compute **Feature Importance & SHAP values** to understand key churn factors  
- Use **Partial Dependence Plots** to assess how features impact churn probability
 <img width="289" alt="eli51" src="https://github.com/user-attachments/assets/c1c6e7ad-3523-4142-b13e-d65222c6994f" />
<img width="290" alt="eli52" src="https://github.com/user-attachments/assets/f6be0866-92c0-4804-81b5-4a948a932288" />

![shap](https://github.com/user-attachments/assets/e122d2ea-a342-401b-86da-33993201492b)

### **5️⃣ Flask Web App Deployment**  
- Build a **user-friendly web app** for real-time churn prediction  
- Display **churn probability, survival curves, hazard curves, and feature impact**  
- Deploy on **Heroku** for easy accessibility  

---

## **📌 Key Insights from Analysis**  
📉 **Tenure Impact** – The longer a customer stays, the lower their churn probability  
📡 **Service Impact** – Customers **without additional services** (e.g., online backup, streaming) are more likely to churn  
📜 **Contract Type** – Customers with **month-to-month contracts** have a higher churn rate  
💳 **Payment Method** – Customers paying via **electronic check** have a higher churn risk  
💰 **Monthly Charges** – Higher monthly charges correlate with higher churn probability  

---

## **🔮 Future Enhancements**  
🔹 **Deep Learning Integration** – Implement LSTMs or Transformer-based models for improved predictions  
🔹 **Real-Time Dashboard** – Develop a **BI-powered dashboard** with live churn insights  
🔹 **Customer Segmentation** – Apply **Clustering (K-Means, DBSCAN)** for targeted retention strategies  
🔹 **Personalized Retention Plans** – Recommend offers based on churn risk & customer behavior  

---

## **🔥 Get Started!**  
🚀 Clone, contribute, and enhance this project! Your feedback and contributions are welcome!  

📌 **GitHub Repo**: [Link to Repository]  

---

Let me know if you need any modifications! 😊
