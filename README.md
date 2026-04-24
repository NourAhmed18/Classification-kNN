# Classification-kNN

# Student Performance Classification using KNN 🎓

## 📌 Description
This project aims to classify student performance into three categories: **Low, Medium, High** using the K-Nearest Neighbors (KNN) algorithm.

---

## 🔍 Project Workflow
- Data Loading & Inspection
- Data Cleaning (removing duplicates, handling missing values)
- Encoding categorical features
- Feature Selection using Correlation Analysis
- Data Visualization (boxplots, heatmaps, pairplots)
- Data Splitting (Train, Validation, Test)
- Feature Scaling (StandardScaler)
- Model Training & Hyperparameter Tuning
- Model Evaluation & Comparison

---

## 🤖 Model Used
- K-Nearest Neighbors (KNN)

---

## ⚙️ Model Optimization
- Tested K values from 1 to 30
- Selected the best K based on validation accuracy
- Used 5-Fold Cross-Validation for better generalization

---

## 📊 Results
- The best K value achieved the highest validation accuracy
- Model performed consistently across training, validation, and test sets
- Cross-validation confirmed model stability

---

## 📉 Evaluation Metrics
- Accuracy Score
- Confusion Matrix
- Precision, Recall, F1-score
- Cross-validation accuracy

---

## 📈 Visualization
- Correlation Heatmap
- Boxplots for outlier detection
- K vs Accuracy curve
- Confusion Matrix for 3-class classification
- Pairplots for feature distribution

---

## 🧠 Key Insights
- "Hours Studied" and "Previous Scores" are the most influential features
- Increasing K helped reduce overfitting
- Feature selection improved model performance
- Cross-validation ensured a reliable evaluation

---

## ⚠️ Overfitting Handling
- Tuned K value (best K = 26)
- Reduced features to the most relevant ones
- Applied cross-validation

---

## 💡 Future Improvements
- Try other models (SVM, Decision Trees)
- Use GridSearch for hyperparameter tuning
- Add more features (attendance, participation)
- Handle class imbalance

---

## 📁 Dataset
Student Performance Dataset

---

## 👩‍💻 Author
Nour Ahmed
