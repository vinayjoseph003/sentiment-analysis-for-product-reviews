# 📝 Sentiment Analysis for Product Reviews  
Machine Learning project to classify customer product reviews into **positive** or **negative** sentiments using traditional ML techniques and TF-IDF text vectorization.

This project is based on an MIT-licensed open-source codebase by **Shreyas Wankhede**, extended and modified with improvements in preprocessing, model selection, and evaluation.

---

## 🔍 Project Overview

This notebook performs end-to-end sentiment analysis, including:

- Cleaning and preprocessing raw text  
- Transforming textual data into numerical vectors using **TF-IDF**  
- Training and comparing classification models  
- Evaluating accuracy and F1-score on training & test sets  
- Visualizing model performance  

The goal is to understand which model generalizes better for sentiment classification.

---

## 📂 Project Structure

```
Sentiment-Analysis/
│
├── Dataset/                   # Contains the product reviews dataset
├── Sentiment_Analysis.ipynb   # Main notebook with complete implementation
└── LICENSE.txt                # MIT License from the original repository
```


---

## 🧼 Data Preprocessing

The following steps were applied to clean the text:

- **Lowercasing**  
- **Tokenization**  
- **Stopword removal**  
- **Removal of special characters & symbols**

The overall pipeline:

<img width="1536" height="1024" alt="ChatGPT Image Nov 16, 2025, 12_13_07 AM" src="https://github.com/user-attachments/assets/440c4b11-ce68-46b4-9409-8c44c3884769" />

---

## 🔠 Feature Extraction

We used **TF-IDF (Term Frequency – Inverse Document Frequency)** to convert text into high-dimensional sparse vectors:

- Captures word importance  
- Works well with linear classifiers  
- Reduces impact of common words  

---

## 🤖 Models Used

Two machine learning models were trained and tested:

### 1️⃣ Logistic Regression  
- Baseline linear classifier  
- Good performance on sparse vectors  

### 2️⃣ Linear SVC (Support Vector Classifier)  
- Margin-based classifier  
- Performs very well on high-dimensional TF-IDF vectors  

---

## 📊 Model Performance

### ✔ Training vs Test Accuracy & F1-Score

| Model              | Accuracy (Train) | Accuracy (Test) | F1-Score (Train) | F1-Score (Test) |
|-------------------|------------------|------------------|-------------------|------------------|
| Logistic Regression | 0.9485           | 0.9013           | 0.9495            | 0.9007           |
| Linear SVC          | **0.9887**       | **0.9008**       | **0.9888**        | **0.9001**       |

---

## 📈 Visualizations

### Accuracy Comparison
<img width="1018" height="547" alt="download" src="https://github.com/user-attachments/assets/8039e3e9-8fdf-47ef-9475-2d21025ff1d6" />


### F1-Score Comparison
<img width="1018" height="547" alt="download" src="https://github.com/user-attachments/assets/54654fe2-62a6-44f3-ab50-9c9ef28684ed" />


---

## 🧪 Conclusion

- **Linear SVC** achieved the highest training accuracy  
- Both models achieved ~90% test accuracy  
- Performance is stable and consistent, showing good generalization  
- TF-IDF + Linear models work extremely well for sentiment analysis tasks  

---

📝 Credits

This project uses an MIT-licensed base code from
Shreyas Wankhede (2019)

Modifications include:
- Error fixing
- Preprocessing improvements
- Model experimentation
- Evaluation visualizations
- Code restructuring

📄 License

This project is licensed under the MIT License.

---

# 🎯 Final Notes

### ✔ This README is 100% safe  
### ✔ Recruiter-friendly  
### ✔ MIT license compliant  
### ✔ Tailored to your notebook  
### ✔ Fully copy-paste ready  

If you want:

✅ A **GitHub description**  
✅ Tags for GitHub  
✅ A professional LinkedIn post for this project  
→ Just tell me!
