# 🛡️ OHS Intelligence Platform

An all-in-one Occupational Health & Safety (OHS) data platform built to predict job task risk levels, visualize workplace safety trends, and collect incident reports in real-time.

This project showcases end-to-end data science and app development skills applied in a critical real-world domain: **worker safety**.

---

## 🚀 Project Modules

| Module | Description                                                                 | Tools Used                                       |
|--------|-----------------------------------------------------------------------------|--------------------------------------------------|
| 1️⃣ Risk Predictor      | Machine Learning model that classifies job tasks as Low, Medium, or High risk.         | Python, Scikit-learn, Pandas, Joblib             |
| 2️⃣ Safety Dashboard    | Interactive data dashboard for visualizing incidents and high-risk trends.             | Streamlit, Seaborn, Plotly, Pandas               |
| 3️⃣ Incident Reporting  | Streamlit form that collects new incident reports and stores them in a database.       | Streamlit, Google Sheets or CSV, Form Handling   |

---

## 💡 Key Features

- Predictive risk classification for job safety assessments
- Visual insights into departments with recurring incidents
- Simple and secure way to record new safety incidents
- Clean, modular architecture for easy updates and scaling

---

## 🧰 Tech Stack

- **Languages**: Python
- **Libraries**: Pandas, Scikit-learn, Matplotlib, Seaborn, Plotly, Joblib
- **Web App**: Streamlit
- **Data Storage**: CSV or Google Sheets

---

## 📁 Project Structure

```bash
OHS-Intelligence-Platform/
│
├── data/                # Raw and cleaned datasets
├── models/              # Saved ML models (e.g., .pkl)
├── notebooks/           # Jupyter notebooks for development
├── app/                 # Streamlit app modules
├── utils/               # Helper scripts (e.g., preprocessing)
├── outputs/             # Charts, visualizations, reports
├── requirements.txt     # Python dependencies
├── README.md            # Project overview
└── .gitignore           # Git ignore rules
