# 🧠 Customer Churn Prediction

This project predicts whether a customer will leave the bank based on their demographics and account details using an SVC classifier built in a scikit-learn pipeline.

---

## 📌 Dataset
- 10,000 customer records
- Features include: Credit Score, Age, Gender, Geography, Balance, Number of Products, Tenure, etc.
- Target: `Exited` – 1 if customer churned, 0 otherwise

---

## ⚙️ Workflow

- Dropped columns: `RowNumber`, `CustomerId`, `Surname`
- Label encoding on categorical features (`Geography`, `Gender`)
- Missing value imputation with `SimpleImputer`
- Feature scaling using `StandardScaler`
- Classification using `SVC` inside a pipeline
- Final model saved as `churn_train_model.pkl`

---

## 💻 Tools & Technologies
- Python
- Pandas, NumPy
- scikit-learn
- Jupyter Notebooks
- Pickle

---

## 📂 Project Structure
CHURN_ANALYSIS/
├── data/
│   └── Churn_Modelling.csv                  
├── model/
│   └── churn_train_model.pkl
├── notebooks/ 
|    ├── churn_train_model.ipynb
|    └── churn_visualize.ipynb 
├── requirements.txt
└── README.md

---

## 🚀 How to Run
1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/customer-churn-analysis.git
   cd customer-churn-analysis
   ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the notebooks:
- Open in Jupyter Notebook or VS Code and run:
- notebooks/churn_train_model.ipynb – for training and pipeline setup
- notebooks/churn_visualize.ipynb – for EDA and visualizations

---

## Output
- Achieved accuracy: ~85%
- Full preprocessing pipeline including label encoding, scaling, and imputation
- Exported model available in model/churn_train_model.pkl for reuse

---

## 😋 Author

**Akshita Aluru**  
📧 aakshitareddy@gmail.com  
🌐 [LinkedIn](https://www.linkedin.com/in/akshita-aluru-7664a1217)