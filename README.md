# 💼 Employee Salary Prediction

This project uses machine learning to predict whether an employee earns more than 50K per year based on features like age, education, job role, work hours, and experience. It includes a user-friendly web app built with Streamlit for both single and batch predictions.

## 🚀 Features

- Predict if an employee earns >50K or ≤50K
- Easy input via sidebar form
- Upload CSV for batch prediction
- Download predictions as a CSV file
- Interactive UI using Streamlit

## 📁 Dataset Used

- **UCI Adult Income Dataset**  
  Source: [https://archive.ics.uci.edu/ml/datasets/adult](https://archive.ics.uci.edu/ml/datasets/adult)

## 🧠 Model Details

- Trained using `scikit-learn`
- Used features: Age, Education, Occupation, Hours-per-week, Experience
- Model saved as `best_model.pkl` using `joblib`

## 🛠️ Technologies & Libraries

- Python
- Pandas, NumPy
- Scikit-learn
- Streamlit
- Joblib

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/jeevan-rp/employee-salary-prediction.git
   cd employee-salary-prediction

employee-salary-prediction/
├── app.py                # Streamlit app
├── best_model.pkl        # Trained model
├── requirements.txt      # Required Python libraries
├── README.md             # Project documentation
