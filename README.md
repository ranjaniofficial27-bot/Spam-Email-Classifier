# 📧 Spam Email Classifier

A machine learning project to detect and filter spam emails based on message content.  
Implemented using **Naive Bayes** and **Support Vector Machines (SVM)** with scikit‑learn.

---

## Project Description
This project builds a text classification pipeline to distinguish between **ham (legitimate)** and **spam** messages.  
It uses:
- **CountVectorizer** for tokenization
- **TF‑IDF Transformer** for feature weighting
- **Multinomial Naive Bayes** and **Linear SVM** for classification

The dataset used is the **SMS Spam Collection Dataset** (available on Kaggle/UCI ML Repository).

---

 Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

 Place the dataset (`spam.csv`) inside the `data/` folder.

Run the classifier:
   ```bash
   python spam_classifier.py
   ```

---

## Sample Outputs

### Naive Bayes Results
```
 Naive Bayes Results
Accuracy: 0.97
              precision    recall  f1-score   support
           0       0.98      0.99      0.98       965
           1       0.94      0.90      0.92       150
```

### SVM Results
```
 SVM Results
Accuracy: 0.98
              precision    recall  f1-score   support
           0       0.99      0.99      0.99       965
           1       0.95      0.93      0.94       150
```

### Confusion Matrix Screenshots
- Naive Bayes Confusion Matrix  
  `[Looks like the result wasn't safe to show. Let's switch things up and try something else!]`

- SVM Confusion Matrix  
  `[Looks like the result wasn't safe to show. Let's switch things up and try something else!]`

---

## Custom Email Test
Example:
```text
Input: "Congratulations! You won a free ticket. Click here to claim."
Naive Bayes → Spam (1)
SVM → Spam (1)
```

---

##  Author Info
Developed by **Ranjani**  
-  Aspiring Machine Learning Engineer  
-  Interested in Deep Learning, Computer Vision, and AI Applications  
-  Contact: ranjaniofficial27@gmail.com  
  
