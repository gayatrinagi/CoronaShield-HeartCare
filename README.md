Post-COVID Heart Risk Prediction System
Overview
This project is an AI-powered web application designed to help individuals assess their potential risk of heart-related complications following COVID-19 recovery. The system leverages user health data and COVID-specific factors such as vaccination status, hospitalization, and time since last vaccine dose to predict heart risk scores and recommend suitable insurance plans.

The app promotes awareness by providing personalized insights and risk predictions but is not a substitute for professional medical advice.

Main Idea
COVID-19 has been linked with lasting cardiovascular complications for some patients. This project addresses the growing need for accessible post-COVID heart health screening by integrating a machine learning model trained on relevant health metrics and COVID-related variables.

By entering basic health information and COVID vaccination details, users receive a risk score indicating their likelihood of post-COVID heart issues, alongside recommended insurance tiers tailored to their risk profile.

Features
User authentication with secure password hashing and account management

Input of detailed health and COVID-related information

Risk prediction using a trained Random Forest model

Personalized insurance premium tier suggestions

Prediction history saved and accessible by users

Interactive UI with Streamlit for easy usage

Tech Stack
Python 3.12

Streamlit — Frontend UI framework for rapid prototyping and deployment

SQLite — Lightweight relational database to store user info and prediction history

Scikit-learn — Machine learning model development (Random Forest classifier)

Joblib — Model serialization and loading

Pandas & NumPy — Data manipulation and preprocessing

Git & GitHub — Version control and project hosting

Installation
Clone the repository:

bash
Copy
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
Install dependencies:

nginx
Copy
pip install -r requirements.txt
Run the app:

arduino
Copy
streamlit run 0_Login.py
Usage
Sign up or log in to the application.

Enter your health details and COVID vaccination information.

Submit the form to get your personalized heart risk prediction and insurance plan suggestion.

View your past prediction history.

Future Enhancements
Integrate larger and region-specific datasets for improved model accuracy.

Expand insurance premium recommendations with real-time data from providers.

Add detailed explanations of predictions (e.g., SHAP value visualizations).

Develop a Flask + React front-end for enhanced UI/UX.

Implement mobile app version for wider accessibility.

License
MIT License

