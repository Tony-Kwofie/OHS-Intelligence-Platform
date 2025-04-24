# 🛡️ Vallberg Civitas Ltd. | OHS Intelligence Platform

## 🏗️ Company Overview: Vallberg Civitas Ltd.

**Vallberg Civitas Ltd.** is a dynamic construction and infrastructure development firm headquartered in **Tallinn, Estonia**, with operations spanning across Northern and Eastern Europe. Founded in 2008, the company delivers strategic infrastructure projects, including urban transit systems, energy facilities, and high-performance commercial structures.

With a skilled workforce of over **1,000 employees**, Vallberg Civitas is committed to engineering excellence, environmental sustainability, and modern construction practices. The company leverages digital design technologies and robust project management systems to ensure timely, cost-effective delivery of complex projects.

**Occupational Health and Safety (OHS)** is a foundational principle in the company’s culture. Vallberg Civitas is ISO 45001 certified and utilizes an integrated safety intelligence platform to track incidents, monitor trends, and identify hazards before they escalate. Through data-driven decision making and frontline engagement, Vallberg Civitas builds not just structures — but safe, thriving environments for everyone involved.


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
