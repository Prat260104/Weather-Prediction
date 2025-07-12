# 🌦️ Weather Prediction Using Naive Bayes Classifier

A machine learning project that predicts whether to **Play** or **Not Play** based on various weather conditions using a **Naive Bayes Classifier**. This project uses a labeled dataset with preprocessing, model training, evaluation, and predictions.

---

## 🧠 Algorithm Used

- **Gaussian Naive Bayes**
  - Assumes features are normally distributed.
  - Simple and effective for probabilistic classification tasks.

---

## 📂 Dataset

- **File:** `large_weather_dataset.csv`
- **Attributes:** Various weather parameters like temperature, humidity, wind, outlook, etc.

---

## 🛠️ Technologies Used

| Tool/Library         | Purpose                                  |
|----------------------|------------------------------------------|
| Python               | Programming language                     |
| Pandas               | Data loading and preprocessing           |
| NumPy                | Numerical operations                     |
| Scikit-learn         | ML model, encoding, evaluation metrics   |
| Matplotlib & Seaborn | Data visualization                       |

---

## ⚙️ Steps Performed

### 📥 1. Data Collection

- Loaded dataset from CSV file.

### 🧹 2. Data Preprocessing

- Removed missing values.
- Encoded categorical features using `LabelEncoder`.
- Normalized numerical values using `StandardScaler`.

### 🤖 3. Model Training

- Split the data into training and test sets.
- Trained a **Gaussian Naive Bayes** classifier using `scikit-learn`.

### 📊 4. Evaluation

- Evaluated the model using:
  - **Accuracy Score**
  - **Classification Report**
  - **Confusion Matrix** (visualized using a heatmap)

### 🔮 5. Prediction

- Compared actual vs predicted labels on the test set.
- Displayed sample predictions.

---

## 🔍 Sample Output

```
Model Accuracy: 0.89

Classification Report:
              precision    recall  f1-score   support
           0       0.88      0.91      0.89        44
           1       0.90      0.86      0.88        43
    accuracy                           0.89        87
   macro avg       0.89      0.89      0.89        87
weighted avg       0.89      0.89      0.89        87
```

---

## 📌 How to Run

1. **Clone the repository:**

```bash
git clone https://github.com/Prat260104/Weather-Prediction.git
cd Weather-Prediction
```

2. **Install dependencies:**

```bash
pip install -r requirements.txt
```

3. **Run the script:**

```bash
python weather_naive_bayes.py
```

---

## 📦 Requirements

Create a `requirements.txt` with:

```
pandas
numpy
scikit-learn
matplotlib
seaborn
```

---

## 👨‍💻 Author

**Prateek Rai**  
🎓 B.Tech in CSE (AI), KIET Group of Institutions  
📘 BS in Data Science, IIT Madras  
🌐 [GitHub: Prat260104](https://github.com/Prat260104)

---

> ⭐ *If you find this project useful, consider giving it a star on GitHub!*
