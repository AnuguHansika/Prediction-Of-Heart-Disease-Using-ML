# Prediction-Of-Heart-Disease-Using-ML
# Heart Disease Prediction Using Machine Learning

## 📌 Project Overview
This project aims to predict **heart disease** using machine learning algorithms based on patient medical data. The model helps in **early diagnosis and risk assessment**, assisting healthcare professionals in decision-making.

## 🚀 Features
- **Multiple ML algorithms** for prediction (Logistic Regression, Random Forest, SVM, etc.).
- **Data preprocessing** (handling missing values, feature scaling, and feature selection).
- **Performance evaluation** using accuracy, precision, recall, and ROC-AUC.
- **API deployment using Flask** for real-time predictions.

## 📊 Dataset
- **Source**: UCI Machine Learning Repository - Heart Disease Dataset.
- **Features**:
  - Age, Sex, Chest Pain Type, Blood Pressure, Cholesterol, Heart Rate, etc.
- **Target Variable**: Presence (1) or Absence (0) of heart disease.

## ⚙️ Technologies Used
- **Programming Language**: Python
- **Libraries**: Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn, Flask
- **Modeling**: Logistic Regression, Random Forest, SVM, Neural Networks
- **Deployment**: Flask API

## 🔧 Setup and Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/heart-disease-prediction.git
   cd heart-disease-prediction
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the model training script:
   ```bash
   python train_model.py
   ```
4. Start the Flask server:
   ```bash
   python app.py
   ```
5. Test the API using Postman or cURL:
   ```bash
   curl -X POST http://127.0.0.1:5000/predict -H "Content-Type: application/json" -d '{"features": [63, 1, 3, 145, 233, 1, 0, 150, 0, 2.3, 0, 0, 1]}'
   ```

## 📈 Model Performance
| Model               | Accuracy |
|---------------------|----------|
| Logistic Regression | 85.4%    |
| Random Forest      | 90.1%    |
| SVM                | 88.7%    |
| Neural Networks    | 91.2%    |

## 🌟 Future Improvements
- Implement **Deep Learning models** (CNNs, RNNs) for improved accuracy.
- Deploy the model as a **web application using Streamlit**.
- Optimize feature selection using **SHAP and LIME** for better interpretability.

