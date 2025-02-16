# 🏥 Stroke Risk Prediction using Machine Learning  

This project classifies individuals based on their risk of **having a stroke** using multiple machine learning models, including **Support Vector Machines (SVM), Random Forest, and Deep Neural Networks**. The model is trained on a dataset from the **CDC**, which tracks **diabetes, hypertension, and stroke conditions** for approximately **70,000 patients**.  

## 🚀 Project Overview  
- **Problem:** Stroke is a leading cause of death and disability worldwide. Early detection can help high-risk individuals take preventive actions.  
- **Solution:** We develop a **stroke risk prediction model** using machine learning techniques, comparing **SVM, Random Forest, and a Deep Neural Network (DNN)**.  
- **Dataset:** Publicly available CDC dataset (~70,000 records) with features such as:
  - Age, Gender
  - Hypertension, Heart Disease
  - BMI, Smoking Status
  - Average Glucose Level
- **Models Used:**
  - **Support Vector Machine (SVM)**
  - **Random Forest Classifier**
  - **Deep Neural Network (DNN) with TensorFlow/Keras**

## 📊 Results Summary
| Model | Accuracy |
|--------|----------|
| Neural Network | 93.58% |
| SVM | 93.65% |
| Random Forest | 93.59% |

📌 **Key Takeaways:**
- **SVM was the best-performing model**, outperforming Random Forest and DNN.
- Feature selection played a crucial role in improving model performance.
- Sensitivity and specificity were evaluated to assess real-world applicability.

---

## 📺 Repository Structure  
```
/stroke-risk-prediction
│── stroke-risk-prediction.ipynb  # Jupyter Notebook with ML models
│── requirements.txt  # Dependencies for running the notebook
│── README.md  # Project documentation
```

---

## 🛠️ Installation & Setup  

### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/YOUR_GITHUB/stroke-risk-prediction.git
cd stroke-risk-prediction
```

### **2️⃣ Install Dependencies**
```bash
pip install -r requirements.txt
```

### **3️⃣ Run the Jupyter Notebook**
```bash
jupyter notebook
```

---

## 👩‍💻 Authors  
- **Himanshi Gupta**
- **Dominik Zeman**
- **Ryan Kan**

---

