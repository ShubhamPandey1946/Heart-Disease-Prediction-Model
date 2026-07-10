# ❤️ Heart Disease Prediction Model

A Machine Learning project that predicts the likelihood of heart disease based on a patient's medical information. The model is trained using supervised learning algorithms and provides predictions that can assist in early diagnosis and healthcare decision-making.

---

## 📌 Features

- Predicts the probability of heart disease.
- Data preprocessing and cleaning.
- Feature selection and normalization.
- Model training using Machine Learning algorithms.
- Performance evaluation using standard metrics.
- Easy-to-use prediction interface.

---

## 🛠️ Tech Stack

- **Programming Language:** Python
- **Libraries:**
  - NumPy
  - Pandas
  - Matplotlib
  - Seaborn
  - Scikit-learn
  - Joblib (for model saving)

---

## 📂 Project Structure

```
Heart-Disease-Prediction/
│── data/
│   └── heart.csv
│
│── models/
│   └── heart_model.pkl
│
│── notebooks/
│   └── Heart_Disease_Prediction.ipynb
│
│── src/
│   ├── preprocess.py
│   ├── train.py
│   ├── predict.py
│   └── utils.py
│
│── requirements.txt
│── README.md
│── LICENSE
```

---

## 📊 Dataset

The project uses the **Heart Disease Dataset**, which contains patient health information such as:

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate
- Exercise-Induced Angina
- ST Depression
- Slope of Peak Exercise ST Segment
- Number of Major Vessels
- Thalassemia
- Target (Heart Disease)

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/Heart-Disease-Prediction.git
cd Heart-Disease-Prediction
```

### 2. Create a virtual environment (Optional)

```bash
python -m venv venv
```

Activate the environment:

**Windows**
```bash
venv\Scripts\activate
```

**Linux/macOS**
```bash
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

### Train the model

```bash
python src/train.py
```

### Make predictions

```bash
python src/predict.py
```

---

## 🤖 Machine Learning Workflow

1. Load dataset
2. Clean and preprocess data
3. Perform feature engineering
4. Split data into training and testing sets
5. Train the machine learning model
6. Evaluate model performance
7. Save the trained model
8. Predict heart disease on new patient data

---

## 📈 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC Score

---

## 🚀 Future Improvements

- Deploy the model using Flask/FastAPI.
- Build an interactive web interface.
- Integrate real-time patient data.
- Experiment with deep learning models.
- Improve accuracy using hyperparameter tuning.

---

## 📸 Sample Output

```
Input Patient Data:
Age: 54
Sex: Male
Chest Pain Type: 2
Cholesterol: 246
Max Heart Rate: 150

Prediction:
✅ Heart Disease Detected

Probability: 87.6%
```

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a new feature branch.
3. Commit your changes.
4. Push to your branch.
5. Open a Pull Request.

---



## 👨‍💻 Author

**Shubham Pandey**

If you found this project helpful, don't forget to ⭐ star the repository!
```
