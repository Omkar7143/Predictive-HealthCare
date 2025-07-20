# 🏥 Predictive HealthCare

**Predictive HealthCare** is a Streamlit-based web application that uses machine learning models to predict the likelihood of three major health conditions:

- 🩺 **Diabetes**
- ❤️ **Heart Disease**
- 🧠 **Parkinson's Disease**

It provides an easy-to-use interface where users can input basic medical information and receive instant predictions based on trained ML models.

---

## 📸 Screenshots
HOMEPAGE

<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/1acb0a92-9f07-4de1-928a-28a1494f9599" />



---

## 🧠 Models & Datasets

| Condition       | Dataset Used                      | Model Used        |
|----------------|------------------------------------|-------------------|
| Diabetes        | `diabetes.csv`                     | Logistic Regression |
| Heart Disease   | `heart_disease_data.csv`           | XGBoost            |
| Parkinson's     | `parkinsons.csv`                   | Random Forest      |

All models are saved using `joblib` and loaded at runtime for fast predictions.

---

## ⚙️ Technologies Used

- **Frontend:** Streamlit  
- **ML Libraries:** Scikit-learn, XGBoost, Joblib  
- **Data Processing:** Pandas, NumPy  
- **Visualization:** Matplotlib, Seaborn  
- **Language:** Python

---

## 🛠️ Installation

### ✅ Prerequisites

- Python 3.7 or higher
- `pip` package manager

### 📦 Clone the Repository

```bash
git clone https://github.com/Omkar7143/Predictive-HealthCare.git
cd Predictive-HealthCare
# Predictive-HealthCare
```
### 📥 Install Requirements

pip install -r requirements.txt

### ▶️ Run the App

streamlit run App.py

### 📁 Project Structure
```bash
Predictive-HealthCare/
│
├── App.py                        # Main Streamlit application
├── requirements.txt              # Project dependencies
├── Streamlit Cmd.txt             # Sample streamlit commands
├── Colab Notebooks/             # Model training & EDA notebooks
│   ├── Diabetes Analysis.ipynb
│   ├── Heart Disease Analysis.ipynb
│   └── Parkinson Analysis.ipynb
│
├── Datasets/                    # Raw data used for training models
│   ├── diabetes.csv
│   ├── heart_disease_data.csv
│   └── parkinsons.csv
│
├── Saved Models/                # Serialized trained models
│   ├── diabetes_model.sav
│   ├── Heart_model.sav
│   └── parkinsons_model.sav
└── README.md                    # You're reading it now 😄
```

### 💡 Features

Real-time predictions for 3 major diseases

Clean and responsive Streamlit UI

Easy to use for medical professionals or students

Pre-trained ML models for fast results

Supports visualization and basic data analysis

### 🤝 Contributing

Pull requests are welcome!

To contribute:
```bash
git clone https://github.com/Omkar7143/Predictive-HealthCare.git
git checkout -b feature/your-feature-name
# Make your changes
git commit -m "Add your message"
git push origin feature/your-feature-name
```
### 📄 License
This project is published as part of a recognized research paper titled "Predictive Analysis for Multiple Diseases" in the Journal for Basic Sciences (JBS), Volume 25, Issue 2, February 2025.

🔒 All rights reserved.

📜 Licensed under academic use and fair educational practices.

📚 UGC Care Group-II Approved | Indexed by Scopus, Google Scholar, Crossref

📝 Author: Omkar Jadhav, GH Raisoni University, Amravati, India.

<img width="1280" height="904" alt="image" src="https://github.com/user-attachments/assets/68cd20a1-6447-4fc0-8a07-5d8f77c2f7e5" />

For permission to reuse code or methodology, please contact via email: omkar.s.jadhav321@gmail.com


### 👨‍💻 Author

Omkar Jadhav

📧 Email: omkar.s.jadhav321@gmail.com

🌐 GitHub: [@Omkar7143](https://github.com/Omkar7143)
