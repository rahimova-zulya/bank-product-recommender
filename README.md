# Bank Product Recommendation System

###  Project Goal
The goal of this project is to create a simple recommendation system that predicts the likelihood of a user accepting a bank's product offer. The recommendation is based on user demographic data and banking activity.

###  Technologies Used:
- **Python** (Pandas, Scikit-learn)
- **Machine Learning**: RandomForestClassifier
- **Data**: Bank Marketing Dataset (UCI)
- **Libraries**: Matplotlib, Seaborn, Gradio (optional for UI)

###  Metrics:
- **Classification**: Accuracy, Precision, Recall, ROC-AUC

###  Dataset:
This project uses the [Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/bank+marketing) from UCI, which contains information about customer demographics and previous bank marketing campaigns.

###  Model:
I train a **RandomForestClassifier** to predict whether a customer will subscribe to a banking product, such as a deposit. The model is evaluated using **ROC-AUC** and **classification metrics**.

###  Key Features:
- User demographic data (age, job, marital status, etc.)
- Financial data (balance, loan, credit status, etc.)
- A simple **RandomForestClassifier** used to predict subscription likelihood

###  Steps:
1. **Data Preprocessing**: Cleaned and encoded categorical variables.
2. **Model Training**: Trained a **RandomForestClassifier** on the preprocessed data.
3. **Evaluation**: Measured model performance with accuracy, precision, recall, and ROC-AUC.
4. **Feature Importance**: Analyzed the most influential features in the prediction.

###  How to Run:
1. Clone the repository:
   ```bash
   git clone https://github.com/rahimova-zulya/Bank_Product_Recommendation_System.git
   cd Bank_Product_Recommendation_System
