🚀 Customer Churn Prediction using Neural Networks

📌 Overview
This project builds an end-to-end Customer Churn Prediction model using a Neural Network (TensorFlow/Keras).
The model predicts whether a customer will leave (churn) or stay based on their data.

🧠 Problem Statement
Customer churn is a major problem for businesses.
This project aims to:
Predict churn in advance
Help companies retain customers

🛠️ Tech Stack
Python
Pandas, NumPy
Scikit-learn
TensorFlow / Keras

⚙️ Workflow
Data Preprocessing
Handling categorical variables (One-Hot Encoding)
Feature scaling (Normalization)
Model Building
Neural Network using Keras
Layers:
Input Layer (Flatten)
Hidden Layers (ReLU)
Output Layer (Sigmoid)
Training
Loss: Binary Crossentropy
Optimizer: Adam
Evaluation using accuracy
Evaluation
Training vs Validation accuracy
Model performance analysis

📊 Model Architecture
Input → Dense(128, ReLU) → Dense(32, ReLU) → Dense(1, Sigmoid)

📈 Results
Achieved good accuracy on training and validation data [79.75 %]
Model successfully predicts customer churn

▶️ How to Run
git clone <your-repo-link>
cd <repo-name>
pip install -r requirements.txt
python main.py

📁 Dataset
Customer data including:
Geography
Gender
Credit score
Balance
Tenure, etc.

🎯 Future Improvements
Hyperparameter tuning
Try different models (XGBoost, Random Forest)
Deploy as a web app

🙌 Author
Anjani Sarawagi
