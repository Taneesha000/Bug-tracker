# 🐞 Bug Tracker App

> A smart, ML-powered bug tracking app to manage issues and predict the most suitable team member for assignment 🔧✨

---

## 📸 Demo Screenshot

> _Example interface (replace with actual screenshot):_

![App Screenshot](https://via.placeholder.com/800x400.png?text=Bug+Tracker+App+Demo)

---

## 🚀 Live Demo

🌐 [Click here to try it on Render](https://bug-tracker-00.onrender.com)  
📦 Powered by: **Streamlit + SQLite + Scikit-learn**

---

## 💡 Features

- 📝 Add, edit, and view bugs with metadata
- 🧠 ML-based assignment of team members using Random Forest Classifier
- 📊 View status and modify existing issues
- 🎯 Clean UI with intuitive UX (Streamlit-based)
- 🧩 Switched to **SQLite** for easy deployment (ideal for Render)

---

## 🗃️ Tech Stack

| Layer        | Tech Used                          |
|--------------|------------------------------------|
| Frontend     | Streamlit                          |
| Backend      | Python + SQLite                    |
| ML           | scikit-learn (RandomForest)        |
| Deployment   | Render                             |
| Data Storage | `bug_data.db` (SQLite DB)          |

---

## 📁 Folder Structure

bug-tracker/
│
├── bug_data.db # SQLite database file
├── login.py # Main Streamlit app with login + navigation
├── issue.py # Issue tracking & prediction logic
├── bugBoard.py # Bug board or visualization module
├── requirements.txt # All Python dependencies
├── README.md # This file ✨
└── render.yaml # Render deployment config


---

## 🛠️ How to Run Locally


git clone https://github.com/Taneesha000/Bug-tracker.git
cd Bug-tracker
pip install -r requirements.txt
streamlit run login.py
---


📦 Deployment (Render)
Create a render.yaml:

yaml
Copy
Edit
services:
  - type: web
    name: bug-tracker-app
    env: python
    buildCommand: pip install -r requirements.txt
    startCommand: streamlit run login.py --server.port=10000 --server.address=0.0.0.0

---

🔮 Future Improvements
Add user registration & roles

Export issue reports as CSV

Add charts & dashboards

Convert to full-fledged Flask/Django app


🤝 Contributors
👩‍💻 Tanisha Gupta - Developer & Maintainer   


    

