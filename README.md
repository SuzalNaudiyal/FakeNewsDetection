

This project detects whether a given news article is **Fake** or **Real** using multiple Machine Learning models.  
Fake news has become a major issue in the digital world, and automated detection is essential to reduce misinformation.

---



Two datasets were used:
- **Fake.csv** → Fake news articles  
- **True.csv** → Real news articles  

Both datasets were merged and preprocessed before model training.


- Text cleaning (lowercasing, punctuation removal)
- Removing URLs, digits, extra symbols
- Normalization
- TF-IDF Vectorization to convert text into numerical features  

---


This project includes training and comparison of **7 ML models**:

| Model | Status |
|-------|--------|
| Logistic Regression | ✅ Trained |
| Decision Tree | ✅ Trained |
| Random Forest | ✅ Trained |
| Gradient Boosting | ✅ Trained |
| AdaBoost | ✅ Trained |
| Support Vector Machine (SVM) | ✅ Trained |
| XGBoost | ✅ Trained |

All models give **95%–99% accuracy** depending on test data.

---

For each model, the following metrics were generated:
- Accuracy
- Precision
- Recall
- F1-Score
- Classification Report



## Copyright
© 2025 Suzal Naudiyal. All rights reserved.

This project is protected under the MIT License.



The notebook includes a function:

```python
manual_testing("Your news text here...")
****
