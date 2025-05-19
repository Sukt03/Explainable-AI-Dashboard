# 📊 Explainable AI Dashboard

An interactive **Streamlit** dashboard for interpreting machine learning models using **SHAP** (SHapley Additive exPlanations).

## 🔍 Features

- 📁 Upload your own CSV datasets  
- 🧠 Automatically detects **classification** or **regression** tasks  
- 🌲 Trains a **Random Forest** model on the fly  
- 🧮 Computes **global feature importance** via SHAP beeswarm plots  
- 🔬 Shows **local feature attribution** with SHAP waterfall plots  
- 💾 Downloadable visualizations for both global and local explanations  
- 🧠 Handles **numerical** and **categorical** features  

<p float="left">
  <img src="https://github.com/user-attachments/assets/a93ed0c3-50c5-431f-b5a2-f6eeb8edfe81" width="800"/>
  <img src="https://github.com/user-attachments/assets/59db57e0-9895-467c-b372-bcc625122116" width="400"/>
  <img src="https://github.com/user-attachments/assets/b62a4d67-d8f6-4f5b-a22d-a3b088de8064" width="400"/>
</p>

---

## 🚀 Instructions to run the Project

Follow these steps to set up the project on your local machine.

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/explainable-ai-dashboard.git
cd explainable-ai-dashboard
```

### 2. (Optional) Create and Activate a Virtual Environment

```bash
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install Required Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Streamlit App

```bash
streamlit run app.py
```

---

## 🧪 Sample Dataset

A sample dataset (sample_regression_data.csv) is included in the repo. It features both numerical and categorical variables for regression task demonstrations.

---

## 🧰 Tech Stack

This project leverages the following tools and libraries:

- 🐍 **Python** — Core programming language used for implementation
- 🎈 **Streamlit** — Interactive web UI framework for data apps
- 🔍 **SHAP** — For model interpretation using Shapley values
- 🧠 **scikit-learn** — For training machine learning models
- 📊 **Matplotlib** — For additional visualizations and plots

---

## 📈 Planned Enhancements

Future iterations of this dashboard aim to include:

- ⚡ **Advanced Model Support** — Integration with popular models like **XGBoost**, **LightGBM**, and **CatBoost**
- 📦 **Pre-Trained Model Upload** — Ability to upload and interpret already trained models
- 📏 **Performance Metrics** — Display evaluation metrics like **Accuracy**, **RMSE**, and **Confusion Matrix**
- 📊 **Model Comparison** — Compare multiple models side-by-side for deeper insights

---
  
