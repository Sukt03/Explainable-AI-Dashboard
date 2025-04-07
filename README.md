Explainable AI Dashboard

A Streamlit-based interactive dashboard for interpreting Machine Learning models using SHAP (SHapley Additive exPlanations).

📌 Features

	•	Upload your own CSV datasets
	•	Automatically detects classification or regression tasks
	•	Trains a Random Forest model
	•	Computes global feature importance with SHAP beeswarm plots
	•	Visualizes local feature attribution using SHAP waterfall plots
	•	Downloadable SHAP visualizations
	•	Handles both numerical and categorical features

![image](https://github.com/user-attachments/assets/a93ed0c3-50c5-431f-b5a2-f6eeb8edfe81)
![image](https://github.com/user-attachments/assets/59db57e0-9895-467c-b372-bcc625122116)
![image](https://github.com/user-attachments/assets/b62a4d67-d8f6-4f5b-a22d-a3b088de8064)


🚀 Getting Started

1. Clone the repository
   git clone https://github.com/YOUR_USERNAME/explainable-ai-dashboard.git
cd explainable-ai-dashboard
2. Create and activate a virtual environment (optional)
   python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
4. Install dependencies
   pip install -r requirements.txt
5. Run the app
   streamlit run app.py

 Sample Dataset

A sample dataset (sample_regression_data.csv) is provided for testing. It includes both categorical and numerical features for regression tasks.




🔧 Tech Stack
	•	Python
	•	Streamlit
	•	SHAP
	•	scikit-learn
	•	Matplotlib

📈 Future Features
	•	Support for XGBoost, LightGBM, and CatBoost models
	•	Upload pre-trained models
	•	Display model performance metrics (accuracy, RMSE)
	•	Compare multiple models
