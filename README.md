# 🩺 Diabetes Predictor

![Python](https://img.shields.io/badge/Python-3.7-blue.svg?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-Web%20App-red.svg?style=for-the-badge&logo=flask&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Predictions-orange.svg?style=for-the-badge)
![Heroku](https://img.shields.io/badge/Heroku-Deployment-purple.svg?style=for-the-badge&logo=heroku&logoColor=white)

## 🔗 [Live Demo](https://predictor-of-diabetes.herokuapp.com/)

An end-to-end machine learning application that predicts whether a patient has diabetes based on diagnostic measurements. This project includes data analysis, model development, and deployment on Heroku as a web application.

## 🎯 Project Overview

Diabetes is a chronic health condition affecting millions of people worldwide. Early detection is crucial for effective management. This project utilizes machine learning to:

- Analyze diagnostic measurements from patients
- Identify patterns associated with diabetes
- Provide quick risk assessment without invasive tests
- Generate downloadable prediction reports for healthcare practitioners

## 📊 Dataset

The model is trained on the **Pima Indians Diabetes Database**, which includes diagnostic measurements for:

- Number of pregnancies
- Glucose concentration
- Blood pressure
- Skin thickness
- Insulin level
- BMI (Body Mass Index)
- Diabetes pedigree function (diabetes hereditary factor)
- Age

Each record is classified as having diabetes (1) or not having diabetes (0).

## 🧠 Machine Learning Pipeline

### Data Preprocessing
- Handling missing values
- Detecting and managing outliers
- Feature scaling and normalization
- Exploratory data analysis (EDA)

### Model Development
The project implements multiple algorithms for comparison:
- Logistic Regression
- Random Forest
- Support Vector Machine
- K-Nearest Neighbors
- Gradient Boosting

After evaluation, the best performing model is selected for deployment.

### Model Evaluation
Performance metrics include:
- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Curve

## 🖥️ Web Application

The Flask-based web application features:
- User-friendly interface for entering diagnostic measurements
- Real-time prediction feedback
- Downloadable prediction results in CSV format
- Comprehensive EDA visualization dashboard

## 🚀 Deployment

The application is deployed on Heroku using:
- Git integration for seamless deployment
- Flask server configuration
- Gunicorn WSGI server
- Environment variables for secure configuration

## 📊 Key Insights

The exploratory data analysis revealed:
- Strong correlation between glucose levels and diabetes diagnosis
- BMI as a significant predictor for diabetes risk
- Age-related patterns in diabetes occurrence
- Important hereditary factors reflected in the diabetes pedigree function

## 🛠️ Technology Stack

- **Language**: Python 3.7
- **Machine Learning**: scikit-learn, pandas, numpy
- **Data Visualization**: matplotlib, seaborn
- **Web Framework**: Flask
- **Deployment**: Heroku
- **Version Control**: Git, GitHub
- **IDE**: Jupyter Notebook

## 📋 How to Run Locally

```bash
# Clone the repository
git clone https://github.com/Dishant27/Diabetes_Predictor.git
cd Diabetes_Predictor

# Set up a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the application
python app.py
```

After running, the application will be available at `http://localhost:5000`.

## 📈 Future Improvements

- Implement more advanced models like Neural Networks
- Add feature importance visualization
- Incorporate confidence intervals for predictions
- Develop a mobile application version
- Integrate with additional health metrics
- Add user authentication for healthcare providers
- Implement longitudinal tracking for patient monitoring over time

## 📚 Resources

- [Pima Indians Diabetes Database](https://www.kaggle.com/uciml/pima-indians-diabetes-database)
- [Flask Documentation](https://flask.palletsprojects.com/)
- [scikit-learn Documentation](https://scikit-learn.org/stable/)
- [Heroku Deployment Guide](https://devcenter.heroku.com/categories/python-support)

## 👨‍💻 Author

Dishant - [GitHub Profile](https://github.com/Dishant27)

---

**Note**: This project is for educational purposes and should not replace professional medical advice. Always consult healthcare providers for diabetes diagnosis and treatment.