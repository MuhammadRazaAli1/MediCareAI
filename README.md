<div align="center">

# 🏥 MediCareAI

### AI-powered multi-disease risk prediction & personal health tracker

Predict **Diabetes**, **Heart Disease** and **Parkinson's** risk in seconds, track your recovery over time, and download a hospital-style PDF report.

![Python](https://img.shields.io/badge/Python-3.9+-0EA5A4?style=for-the-badge&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-App-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-Charts-7C3AED?style=for-the-badge&logo=plotly&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-Database-0F172A?style=for-the-badge&logo=sqlite&logoColor=white)

</div>

---

## ✨ Features

| | Feature | What you get |
|---|---|---|
| 🔐 | **Secure accounts** | Register, sign in, personal health profile |
| 📊 | **Smart dashboard** | Risk trends, latest result per disease, activity feed |
| 🩸❤️🧠 | **3 AI predictors** | Diabetes, Heart Disease, Parkinson's with a live risk gauge |
| 🕘 | **Health history** | Every checkup saved, charted and deletable |
| 📈 | **Recovery tracker** | Compare latest vs previous: *Improving, Stable or Worsening* |
| 📄 | **PDF medical report** | Professional report with advice and recovery comparison |

## 🚀 Quick Start

```bash
git clone https://github.com/MuhammadRazaAli1/MediCareAI.git
cd MediCareAI
pip install -r requirements.txt        # Python 3.9+
streamlit run app.py                   # opens http://localhost:8501
```

Create an account, pick a module from the sidebar, enter the values and click **Run AI Prediction**.
Models train automatically on first launch if no saved model is found.

## 🧠 The Models

| Module | Algorithm | Inputs |
|---|---|---|
| 🩸 Diabetes | Random Forest (220 trees) | 8 clinical values |
| ❤️ Heart Disease | Gradient Boosting | 13 cardiac values |
| 🧠 Parkinson's | Random Forest | 22 voice biomarkers |

Every prediction returns a probability and a risk band:

`🟢 Low < 30%` · `🟡 Moderate 30-60%` · `🟠 High 60-80%` · `🔴 Very High 80%+`

## 🔄 How It Works

```
 Sign in --> Enter clinical values --> ML model --> Risk probability + advice
                                                          |
                          Saved to database <-------------+
                                |
        Dashboard  ·  History  ·  Recovery Tracker  ·  PDF Report
```

## 📁 Project Structure

```
MediCareAI/
├── app.py              # entry point and page routing
├── core/               # database, ML models, helpers, PDF report
├── interface/          # UI styling and page sections
├── trained_models/     # saved .joblib models
└── requirements.txt
```

## 🛠️ Tech Stack

**Python** · **Streamlit** · **scikit-learn** · **pandas / NumPy** · **Plotly** · **SQLite** · **fpdf2**

## ⚠️ Disclaimer

MediCareAI is an educational project. The models are trained on **synthetically generated data**, not real patient records, so results are **not medical advice** and must never replace a qualified doctor.

---

<div align="center">

Built with ❤️ by **[Muhammad Raza Ali](https://github.com/MuhammadRazaAli1)**

⭐ If you like this project, give it a star!

</div>
