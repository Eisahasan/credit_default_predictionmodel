# Credit Card Behaviour Score Prediction

## 📌 Objective

The goal of this project is to improve the **credit risk management framework** of a bank by developing a forward-looking **Behaviour Score**—a classification model that predicts whether a credit card customer will default in the following month.

Using historical behavioral data from over **30,000 customers**, a **binary classification model** was developed to help the bank:

- Flag potential defaulters in advance
- Adjust credit exposure proactively
- Trigger early warning systems
- Prioritize risk-based actions

---

## 🔁 Project Workflow

### 1. Data Preprocessing

- **Missing Value Handling**: All missing values in the `age` column were imputed with the column mean.
- **Data Type Fixes**: Columns like `age`, `marriage`, `education`, and `sex` were appropriately cast to the correct data types.

---

### 2. EDA and Financial Insights

#### 📊 Visualizations

- Used **Matplotlib** and **Seaborn** to create:
  - **Heatmaps** to analyze correlation
  - **Histograms** and **Countplots** for distribution and class balance

#### 💡 Financial Insights

- Insights from the plots revealed how customer behavior (like late payments, bill amount patterns, and credit limit) significantly influences **default risk**.

---

### 3. Feature Engineering

Created additional financial features to enhance model learning:

- **Deliquency Count**: Number of months with payment delays
- **Max Delay**: Longest delay in credit payment
- **Average Pay Amount**: Mean of all payment amounts across months
- **Utilization Ratio**: Ratio of average bill amount to credit limit

---

### 4. Handling Class Imbalance

- The dataset showed significant class imbalance.
- Applied **downsampling** of the majority class and **class weighting** during model training to address this issue.

---

### 5. Model Training and Selection

- Multiple classifiers were trained: **Logistic Regression**, **Decision Tree**, **XGBoost**, and **LightGBM**
- **XGBoost** was selected based on superior performance, especially its **F2-score** (which emphasizes recall).
- A custom **classification threshold** (less than 0.5) was chosen to improve sensitivity to defaults.

---

## 🧑‍💻 Author

**Eisa Hasan**  

O.P. Jindal Global University

---


---



