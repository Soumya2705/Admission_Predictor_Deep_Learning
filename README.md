# 🎓 Admission Predictor using Deep Learning (ANN)

## 📌 Project Overview
This project focuses on predicting the chances of admission using Deep Learning techniques based on student academic profiles.

The goal is to analyze admission-related factors and build an Artificial Neural Network (ANN) model to predict admission probability effectively.

The project demonstrates a complete machine learning and deep learning workflow, including:

- Data preprocessing  
- Feature selection  
- Model building (ANN)  
- Model training  
- Model evaluation  

---

## 📂 Dataset
The dataset contains student information such as:

- GRE Score  
- TOEFL Score  
- University Rating  
- SOP (Statement of Purpose)  
- LOR (Letter of Recommendation)  
- CGPA  
- Research Experience  
- Chance of Admit  

📁 Dataset included in repository:
`Admission_Predict.csv`

---

## 🛠️ Tools & Libraries Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn  
- TensorFlow / Keras  
- Jupyter Notebook  

---

## 🧹 Data Preprocessing
The dataset was cleaned and prepared using the following steps:

- Removed unnecessary columns (e.g., Serial No.)  
- Checked and handled missing values  
- Feature scaling (Normalization/Standardization)  
- Split data into training and testing sets  

---

## 🤖 Model Implemented

### 1️⃣ Artificial Neural Network (ANN)
- Input Layer: Based on number of features  
- Hidden Layers: Fully connected dense layers  
- Activation Functions: ReLU  
- Output Layer: Sigmoid (for probability prediction)  

---

## 📊 Model Training
- Optimizer: Adam  
- Loss Function: Mean Squared Error (MSE)  
- Epochs: Defined during training  
- Batch Size: Configured for optimal performance  

---

## 📈 Model Evaluation
The model was evaluated using:

- Mean Squared Error (MSE)  
- Mean Absolute Error (MAE)  
- R² Score  

---

## 🔍 Key Insight
- CGPA and GRE Score are the most influential features  
- ANN captures non-linear relationships better than basic regression  
- Proper scaling significantly improves performance  

---

## 📉 Problem Observed
- Small dataset limits deep learning performance  
- Risk of overfitting  
- Requires careful tuning of hyperparameters  

---

## 🚀 Improvements Applied
- Feature scaling  
- Model tuning (layers, neurons)  
- Evaluation using multiple metrics  

---

## 🔬 Model Analysis
- Impact of hidden layers  
- Effect of activation functions  
- Performance comparison with basic regression  

---

## ▶️ How to Run

1. Clone the repository  
2. Open the project folder in VS Code or Jupyter  
3. Install required libraries:

```bash
pip install pandas numpy matplotlib scikit-learn tensorflow
