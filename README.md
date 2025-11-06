🏥 Health Premium Prediction using Machine Learning

This project predicts health insurance premium amounts based on user details such as age, BMI, gender, smoking habits, and region. It combines data preprocessing, model training, and a Streamlit web interface to make predictions easily accessible.

🔗 Live Demo: Health Premium Prediction App

🚀 Project Overview

Health insurance premium prediction helps companies estimate customer costs and assists individuals in understanding their expected premiums.
This project applies Machine Learning techniques such as Regression Models and XGBoost to predict the insurance cost accurately.

⚙️ Tech Stack

Category	Tools / Libraries
Language	Python
Framework	Streamlit
Libraries	pandas, numpy, scikit-learn, xgboost, joblib
Environment	PyCharm, GitHub, Streamlit Cloud

📊 Features

✅ Data preprocessing and feature encoding
✅ Model training using XGBoost Regressor
✅ Saved trained model using Joblib
✅ User-friendly Streamlit web app for predictions
✅ Real-time premium prediction based on input values

🧠 Machine Learning Workflow

Data Collection – Collected health-related attributes such as age, BMI, and smoking status.
Data Preprocessing – Cleaned and encoded categorical features.
Model Building – Trained various models (Linear Regression, Decision Tree, XGBoost).
Evaluation – Compared performance and selected the best model.
Deployment – Deployed using Streamlit Cloud for public use.

📦 Installation

To run this project locally, follow these steps 👇

# Clone the repository
git clone https://github.com/htppsazhar/Health-premium-prediction-ML.git

# Navigate to the project directory
cd Health-premium-prediction-ML

# Install dependencies
pip install -r requirements.txt

# Run the Streamlit app
streamlit run main.py

📁 Project Structure
Health-premium-prediction-ML/
│
├── main.py                  # Streamlit app entry point
├── prediction_helper.py     # Contains prediction logic
├── requirements.txt         # Dependencies list
├── runtime.txt              # Python version info for Streamlit Cloud
├── artifacts/               # Stores trained model files
├── README.md                # Project documentation
└── LICENSE                  # License file

🧩 Example Prediction

Enter the following sample values in the app:

Age: 35
BMI: 28.5
Children: 2
Smoker: No
Region: Southeast

👉 The app will instantly predict the estimated insurance premium.

🧑‍💻 Author
Azhar Ullah Khan
📍 Data Analyst & Machine Learning Enthusiast
🔗 LinkedIn Profile

🔗 GitHub Profile

🪪 License

This project is licensed under the MIT License – feel free to use, modify, and share it with proper credits.
