# DAI-101
# 📊 Customer Churn Analysis - Data Exploration & Visualization

## 🛠 Instructions
⚠️ If this Python notebook does not open in **GitHub** or shows a rendering issue:  

- **Clone this repository** and open the `.ipynb` file in **Jupyter Notebook** on your laptop.  


---

## ✍️ Author
Anjani Nandan 23112017
Chemical Engineering  


---

##  Project Overview
This project performs **Exploratory Data Analysis (EDA)** on a **customer churn dataset** to uncover key insights and trends.  
By analyzing **demographics, account activity, and churn status**, we identify the most critical factors contributing to **customer attrition**.

###  Key Objectives:
- Perform **data cleaning & preprocessing**
- Conduct **univariate, bivariate, and multivariate analysis**
- Detect **outliers** using **IQR method**
- Use **groupby() analysis** for deeper insights  
- Visualize **churn trends** and correlations

---

## 📂 Dataset Overview
The dataset consists of customer details, including **demographics, financial metrics, and churn status**.

###  **Numerical Features**:
- `CreditScore`
- `Age`
- `Balance`
- `NumOfProducts`
- `EstimatedSalary`

###  **Categorical Features**:
- `Geography` (France, Germany, Spain)
- `Gender` (Male, Female)
- `HasCrCard` (Credit card ownership)
- `IsActiveMember` (Bank activity status)
- `Exited` (Churn status: 1 = Churned, 0 = Retained)

---

## Workflow

### 1. Data Cleaning**
- Handled missing values  
- Ensured **consistent data types**  
- Checked for **duplicate records**  

---

### 📊 **2. Univariate Analysis**
- **Numerical Features**: Distribution plots for **Age, Credit Score, Balance, etc.**
- **Categorical Features**: Count plots for **Gender, Geography, Active Membership, etc.**  

📌 **Example Code:**
```python
sns.histplot(df["Age"], kde=True, bins=30)
plt.title("Age Distribution")
plt.show()

