# **Credit Card Fraud Detection**

This project focuses on detecting fraudulent transactions within a dataset of credit card transactions. It applies **data analysis**, **visualization techniques**, and **machine learning models** to identify patterns and anomalies indicating fraud.

---

## **Dataset**

The dataset `creditcard.csv` includes the following features:

- **Time**: Seconds elapsed between this transaction and the first transaction in the dataset.
- **V1-V28**: Features transformed via Principal Component Analysis (PCA) to maintain confidentiality.
- **Amount**: Transaction amount.
- **Class**: Target variable (1 = fraudulent, 0 = legitimate).

---

## **Project Structure**

### **1. Data Loading and Exploration**

- Uses libraries such as `numpy`, `pandas`, `seaborn`, and `matplotlib` for data manipulation and visualization.
- Analyzes dataset structure, size, and basic statistics.

### **2. Data Preprocessing**

- Addresses class imbalance with undersampling or oversampling techniques.
- Scales numerical features like `Amount` for improved model performance.

### **3. Exploratory Data Analysis (EDA)**

- Examines the distribution of legitimate vs. fraudulent transactions.
- Conducts correlation analysis of features.
- Visualizes patterns in the data.

### **4. Model Training and Evaluation**

- Implements machine learning models, including:
  - **Logistic Regression**
  - **Random Forest**
  - **Support Vector Machines (SVM)**
  - **Neural Networks**
- Evaluates performance using metrics such as:
  - **Accuracy**
  - **Precision**
  - **Recall**
  - **F1-Score**
  - **Area Under the Curve (AUC)**

### **5. Results**

- Compares the performance of different models.
- Highlights features contributing significantly to fraud detection.

---

## **Requirements**

- **Python 3.7+**
- **Required Libraries**:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`
  - `imbalanced-learn`

To install dependencies:

```bash
pip install -r requirements.txt
