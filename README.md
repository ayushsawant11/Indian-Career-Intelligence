# 🇮🇳 India Career Intelligence
**An End-to-End MLOps System for the Indian Tech Job Market**

### 📌 Project Overview
This project is a comprehensive machine learning pipeline designed to decode the nuances of the Indian job market. By leveraging real-world data from **Naukri.com**, the system provides data-driven insights into salary trends, skill demands, and job seniority across major Indian tech hubs like **Mumbai**, **Bengaluru**, and **Gurugram**.

### 🚀 Key Features
* **Salary Predictor**: An **XGBoost** regression model that estimates salary ranges (₹ LPA) based on role, location, years of experience, and tech stack.
* **Explainable AI (XAI)**: Utilizes **SHAP values** to identify which specific skills (e.g., AWS, PyTorch, React) provide the highest salary "bump".
* **JD Skill Extractor**: An NLP tool fine-tuned on **DistilBERT** to extract key technical skills and classify seniority levels.
* **Company Tier Classifier**: A **PyTorch-based CNN** that identifies company tiers (Tier-1, Tier-2, Startups).
* **Production-Ready API**: All models are served via a **FastAPI** backend and containerized with **Docker**.

### 🛠️ Tech Stack
* **Languages**: Python (Pandas, Scikit-Learn, PyTorch)
* **Machine Learning**: XGBoost, SHAP, HuggingFace Transformers
* **DevOps**: Docker, FastAPI, GitHub Actions (CI/CD)
* **UI/Demo**: Gradio & HuggingFace Spaces


### 👨‍💻 Author
**Ayush Sawant** *3rd Year AI & Data Science Student*
