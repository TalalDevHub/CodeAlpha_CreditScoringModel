# Credit Scoring Model

A machine learning project that predicts the likelihood of credit default using historical customer data. The model is trained on the Kaggle **German Credit Risk** dataset, applying data preprocessing, feature engineering, and classification algorithms to assess creditworthiness. Includes model evaluation, performance metrics, and visualizations for insights.

---

## 📂 Project Structure

├── data/ # Dataset files
├── notebooks/ # Jupyter notebooks for EDA, modeling, and evaluation
├── src/ # Python scripts for preprocessing and model training
├── requirements.txt # Python dependencies
├── README.md # Project documentation
└── results/ # Saved models and evaluation outputs

---

## 📊 Dataset

- **Name:** German Credit Risk Dataset  
- **Source:** [Kaggle - German Credit Data](https://www.kaggle.com/datasets/uciml/german-credit)  
- **Size:** 1,000 entries, 20 features  
- **Target Variable:** Credit Risk (Good / Bad)

**Features include:**
- Status of existing checking account
- Duration in months
- Credit history
- Purpose of the loan
- Credit amount
- Employment status
- Personal status and sex
- Age in years
- Housing type
- Number of existing credits

---

## 🛠️ Technologies Used

- **Python** — Programming language
- **Pandas** — Data manipulation
- **NumPy** — Numerical computations
- **Matplotlib / Seaborn** — Data visualization
- **Scikit-learn** — Machine learning models and evaluation
- **Jupyter Notebook** — Interactive analysis and development

---

## 📈 Workflow

1. **Data Loading**  
   Import and inspect the dataset.

2. **Exploratory Data Analysis (EDA)**  
   - Visualize feature distributions  
   - Identify correlations  
   - Check for missing values

3. **Data Preprocessing**  
   - Encode categorical variables  
   - Scale numerical features  
   - Handle missing values

4. **Model Building**  
   - Logistic Regression  
   - Random Forest  
   - Gradient Boosting

5. **Model Evaluation**  
   - Accuracy, Precision, Recall, F1-score  
   - Confusion Matrix  
   - ROC-AUC curve

6. **Results & Insights**  
   - Feature importance analysis  
   - Recommendations

---

## 📌 Results Summary

- **Best Model:** Random Forest Classifier  
- **Accuracy:** ~85%  
- **Key Features Influencing Credit Risk:**
  - Credit history
  - Credit amount
  - Duration of credit
  - Status of checking account

---

## 🚀 How to Run

1. **Clone the repository**
   git clone https://github.com/TalaDevHub/CodeAlpha_CreditScoringModel.git
   cd credit-scoring-model
2. **Install Dependencies**
   pip install -r requirements.txt
3. **Run the Jupyter Notebook**
   jupyter notebook notebooks/credit_scoring.ipynb
