

# 🏦 Loan Default Prediction of a Bank

### Predicting Loan Default Risk Using Machine Learning

---

## 📖 Overview

This project develops a robust **machine learning model** to predict loan defaults for a banking institution.

By analyzing financial and demographic attributes of loan applicants, the model identifies individuals likely to default. This enables banks to:

* Make informed lending decisions
* Reduce financial risk
* Improve portfolio quality
* Strengthen credit risk management

The complete workflow is implemented in a **Jupyter Notebook**, covering:

* Data exploration
* Data preprocessing
* Feature engineering
* Model training
* Model evaluation

---

## ✨ Key Features

* ✅ **Data Loading & Preprocessing**

  * Loads dataset from `hmeq.csv`
  * Handles missing values
  * Prepares features for modeling

* 📊 **Exploratory Data Analysis (EDA)**

  * Numerical feature distributions
  * Categorical feature relationships
  * Target variable analysis

* 🚨 **Outlier Detection**

  * IQR-based detection
  * DBSCAN-based outlier handling

* 🧠 **Feature Engineering**

  * Improves predictive performance
  * Handles categorical encoding

* 🤖 **Machine Learning Modeling**

  * Classification model for predicting `BAD` (loan default)
  * Hyperparameter tuning
  * Cross-validation

* 📈 **Model Evaluation**

  * Accuracy
  * Precision
  * Recall
  * F1-score
  * ROC-AUC
  * Confusion Matrix

* 📊 **Extensive Visualizations**

  * Boxplots
  * Categorical plots
  * Heatmaps
  * Numerical distributions

---

## 🖼️ Visualizations

The repository includes multiple visualization directories generated during EDA and model evaluation.

### 📦 Boxplots

Used to visualize distributions and detect outliers.

<img width="1500" height="2000" alt="DEBTINC_boxplot" src="https://github.com/user-attachments/assets/5b3677ea-780c-48f4-9ba2-f98355b6d1b5" />

---

### 📊 Categorical Plot Example

<img width="1962" height="1638" alt="default_rate_heatmap_JOB_vs_REASON" src="https://github.com/user-attachments/assets/ecf9d64a-f0f5-44a0-85e2-1ad0d0152a4a" />

---

### 📉 Numerical Plot Example

<img width="1800" height="1200" alt="DEBTINC_vs_BAD" src="https://github.com/user-attachments/assets/80d5a63c-74f7-47fa-b0a3-ab4df3eac727" />

---

## 🛠️ Tech Stack

### 👨‍💻 Programming Language

* Python 3.x

### 📚 Libraries Used

* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 🚀 Quick Start

### 🔹 Prerequisites

* Python 3.x
* pip

---

### 🔹 Clone the Repository

```bash
git clone https://github.com/dipta19062021/Loan_Default_Prediction_of_a_bank.git
cd Loan_Default_Prediction_of_a_bank
```

---

### 🔹 Create Virtual Environment (Recommended)

```bash
python -m venv venv

# Windows
.\venv\Scripts\activate

# macOS/Linux
source venv/bin/activate
```

---

### 🔹 Install Dependencies

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

---

### 🔹 Run the Notebook

```bash
jupyter notebook
```

Then open:

```
loan prediction.ipynb
```

Run cells sequentially to perform:

* Data loading
* EDA
* Preprocessing
* Model training
* Evaluation

---

## 📁 Project Structure

```
Loan_Default_Prediction_of_a_bank/
│
├── .ipynb_checkpoints/               
├── Loan Default Prediction dummy project.docx
├── Loan Default Project.docx         
├── boxplots/                         
├── boxplots_dbscan/                  
├── categorical_plots/                
├── hmeq.csv                          
├── loan prediction.ipynb             
└── numerical_plots/                  
```

---

## 📚 Documentation

* **Loan Default Project.docx**
  → Detailed methodology, findings, and conclusions

* **Loan Default Prediction dummy project.docx**
  → Supplementary or draft documentation

---

## 🤝 Contributing

Contributions are welcome!

To contribute:

1. Follow installation steps above
2. Create a new branch
3. Make improvements
4. Submit a Pull Request

You can:

* Improve model performance
* Add new algorithms
* Improve documentation
* Optimize preprocessing

---

## 📄 License

This project is currently not licensed.
Please contact the repository owner for licensing details.

---

## 🙏 Acknowledgments

Special thanks to:

* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Project

For providing powerful tools for data science and machine learning.

---

## 📞 Support

* 🐛 Open an Issue via GitHub
* 📧 Contact the repository owner directly

---

⭐ If you find this project useful, consider giving it a star!

---

If you’d like, I can also:

* Add professional GitHub badges (Python version, license, build status)
* Add a Results section with model metrics
* Make it more resume-ready for placements
* Or convert it into a research-style project documentation

You’re honestly building this very nicely — just polishing now 😊
