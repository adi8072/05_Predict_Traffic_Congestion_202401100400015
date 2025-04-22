# 05_Predict_Traffic_Congestion_202401100400015
This project uses machine learning to classify traffic congestion levels—Low, Medium, or High—based on sensor data. By training a Random Forest model, it enables accurate predictions that support smart city traffic management and reduce urban mobility issues.
# 🚦 Traffic Congestion Prediction using Random Forest

This project uses machine learning to classify traffic congestion levels — **Low**, **Medium**, or **High** — based on traffic sensor data. The goal is to support smarter urban traffic management through predictive modeling.

---

## 📁 Dataset

- **File**: `traffic_congestion.csv`
- **Description**: Contains features collected from traffic sensors to indicate conditions like vehicle count, average speed, time of day, etc.
- **Target Variable**: `congestion_level` (values: Low, Medium, High)

---

## ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib & Seaborn (for data visualization)
- Scikit-learn (for machine learning)

---

## 🧠 Algorithm Used

- **Random Forest Classifier**: An ensemble learning algorithm based on multiple decision trees that combines their outputs to improve accuracy and reduce overfitting.

---

## 📌 Project Workflow

1. **Data Loading**: Upload and preview the dataset.
2. **Preprocessing**:
   - Handle missing values.
   - Encode categorical variables.
   - Scale numerical features.
3. **Model Training**:
   - Split data into training and testing sets.
   - Train a Random Forest Classifier.
4. **Model Evaluation**:
   - Generate a classification report.
   - Display a confusion matrix.
   
![Screenshot 2025-04-22 143422](https://github.com/user-attachments/assets/093cfe26-4e6f-4b4e-be44-4d1e7c4fc870)
![Screenshot 2025-04-22 143448](https://github.com/user-attachments/assets/ea0dfdb3-44f5-4267-a6ba-7e5a4ca0a337)

---

## 🧾 How to Run the Code

1. Open the project in [Google Colab](https://colab.research.google.com/).
2. Upload the dataset using:
   ```python
   from google.colab import files
   uploaded = files.upload()
