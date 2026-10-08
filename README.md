🫀 Heart Disease Prediction Using Machine Learning
An interactive machine learning web application that predicts the likelihood of heart disease based on various patient health and clinical parameters.

📌 About the Project
Heart Disease Prediction Using Machine Learning is a classification-based project designed to demonstrate how machine learning can be applied to healthcare-related data.
The application takes important patient parameters as input, processes them using the same preprocessing pipeline used during model training, and generates a prediction through an easy-to-use Streamlit interface.
The project covers the complete machine learning workflow, including data preprocessing, feature transformation, model training, model serialization, and deployment through a web application.
⚠️ Disclaimer: This project is intended for educational and demonstration purposes only. It is not a medical diagnostic tool and should not be used as a substitute for professional medical advice.

✨ Features
- 🩺 Interactive heart disease prediction
- 🤖 Machine learning classification model
- 📊 Multiple clinical and health-related parameters
- ⚙️ Feature preprocessing and scaling
- 🌐 Streamlit-based web interface
- 🚀 Real-time prediction
- 💾 Saved trained model and preprocessing components
- 🐍 Built completely with Python
  
📥 Input Parameters
The application uses several health and clinical parameters, including:
Parameter	Description
Age	Age of the patient
Sex	Biological sex
Chest Pain Type	Type of chest pain experienced
Resting BP	Resting blood pressure
Cholesterol	Serum cholesterol level
Fasting Blood Sugar	Whether fasting blood sugar is above the specified threshold
Maximum Heart Rate	Maximum heart rate achieved
Exercise-Induced Angina	Presence of exercise-induced angina
Oldpeak	ST depression induced by exercise
ST Slope	Slope of the peak exercise ST segment


🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Streamlit
- Jupyter Notebook
- Pickle

📂 Project Structure
Heart-Disease-Prediction/
│
├── app.py
├── heart.csv
├── heart.ipynb
├── heart_columns.pkl
├── heart_scaler.pkl
├── KNN_heart.pkl
├── requirements.txt
└── README.md

File Description
- app.py — Streamlit application used for prediction.
- heart.csv — Dataset used for the project.
- heart.ipynb — Jupyter Notebook containing data analysis, preprocessing, and model development.
- KNN_heart.pkl — Saved trained machine learning model.
- heart_scaler.pkl — Saved feature scaler used during preprocessing.
- heart_columns.pkl — Saved feature/column information required by the prediction pipeline.
- requirements.txt — Python dependencies required to run the project.
- README.md — Project documentation.
  
🚀 Installation & Setup
1. Clone the Repository
git clone https://github.com/your-username/heart-disease-prediction.git
Move into the project directory:
cd heart-disease-prediction
2. Create a Virtual Environment (Optional)
python -m venv venv
Activate it on Windows:
venv\Scripts\activate
3. Install Dependencies
pip install -r requirements.txt
If you do not have a requirements.txt file, you can install the main dependencies using:
pip install pandas numpy scikit-learn streamlit
4. Run the Streamlit Application
Run the application using:
python -m streamlit run app.py
Alternatively:
streamlit run app.py
After running the command, Streamlit will provide a local URL, usually:
http://localhost:8501
Open the URL in your browser to use the application.
🔄 Machine Learning Workflow
The project follows a typical machine learning pipeline:
Dataset
   ↓
Data Preprocessing
   ↓
Feature Selection
   ↓
Feature Scaling
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Model Serialization
   ↓
Streamlit Deployment
   ↓
User Input
   ↓
Prediction
The trained model and preprocessing objects are saved using Python's pickle module and loaded by the Streamlit application during prediction.

🎯 Project Objective
The primary objective of this project is to build an end-to-end machine learning application that demonstrates how a classification model can be integrated into a user-friendly web interface.
It provides practical experience with:
- Data preprocessing
- Exploratory data analysis
- Feature engineering
- Feature scaling
- Machine learning classification
- Model serialization
- Streamlit application development
- Model deployment concepts

📊 Future Improvements
Some possible improvements for the project include:
- Comparing multiple machine learning algorithms
- Adding model performance metrics to the application
- Displaying prediction probability
- Improving the user interface and visualizations
- Adding model explainability using techniques such as SHAP
- Deploying the application online
- Adding automated model retraining
  
👨‍💻 Author
Kartikey Sinha
This project was developed as part of my learning journey in Machine Learning and Data Science.

⭐ Support
If you find this project useful, consider giving the repository a ⭐ on GitHub!
