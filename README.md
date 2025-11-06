#  PrediTech - Predictive Maintenance System

This project focuses on building a **Predictive Maintenance System** that detects potential **machine failures** using real-time sensor data and machine learning models.  
It involves **data cleaning, feature engineering, exploratory data analysis (EDA), model training, optimization, and deployment** using Streamlit.

---

##  Key Steps
- Data import and cleaning  
- Feature engineering (`Power`, `Temp_Diff`, `Torque_Speed_Ratio`)  
- Outlier and correlation analysis  
- Feature scaling and encoding  
- Model comparison across Logistic Regression, Random Forest, SVM, XGBoost, CatBoost, and LightGBM  
- Model optimization using RandomizedSearchCV  
- Deployment using Streamlit for real-time failure detection  

---

##  Tools Used
- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)  
- **LightGBM**, **XGBoost**, **CatBoost**  
- **Streamlit** (for model deployment)  
- **Pickle** (for saving and loading trained model)  
- **Jupyter Notebook**, **VS Code**

---

##  Model Performance
**Best Model:** LightGBM  
| Metric | Score |
|---------|--------|
| **Accuracy** | 99% |
| **Precision** | 98% |
| **Recall** | 81% |
| **F1-Score** | 0.89 |

After optimizing the LightGBM model, performance metrics significantly improved, confirming its robustness and predictive strength.

---

##  Key Insights
- **Tool Wear**, **Power**, and **Rotational Speed** are the most influential indicators of machine failure.  
- **Temperature Difference** also plays a crucial role in detecting stress conditions.  
- Outliers often indicate real mechanical stress — they were retained rather than removed.  
- The model enables early failure detection, reducing downtime and maintenance costs.

---

##  Streamlit App Features
- Real-time failure detection using sensor inputs  
- Scaled and encoded preprocessing for user input consistency  
- Visual and textual prediction outputs (Normal / Failure)  
- link to the streamlit app : https://preditech-predictive-maintenance.streamlit.app/

---
##  Conclusion

This project successfully developed a Predictive Maintenance System capable of identifying potential machine failures before they occur.
The optimized LightGBM model achieved exceptional accuracy and reliability, ensuring that failures can be detected early, reducing downtime and operational costs.

By integrating machine learning with real-time monitoring, this system enables industries to transition from reactive to proactive maintenance, improving efficiency, safety, and productivity.
Deployment with Streamlit makes the model easily accessible for field technicians and engineers.
---

##  Acknowledgment

This project was developed by the PrediTech Group as part of the TechCrush Data Science & AI Capstone Program.
Special thanks to TechCrush for the mentorship, guidance, and resources that made this project possible from concept to final deployment.
---

##  How to Use
Clone the repository:  
```bash
git clone https://github.com/benmill52/predictive-maintenance-system.git
