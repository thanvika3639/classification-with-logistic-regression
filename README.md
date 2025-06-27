# classification-with-logistic-regression

✅ Steps Performed
1. Load and Clean Data
Dropped unused columns like id and empty Unnamed: 32.

Encoded diagnosis column: M → 1, B → 0.

2. Split and Standardize
Split into training and testing sets (80/20).

Applied StandardScaler to normalize features.

3. Train Model
Used LogisticRegression() from Scikit-learn.

4. Evaluate Performance
Confusion Matrix

Classification Report: Precision, Recall, F1-score

ROC-AUC Score: 0.997

ROC Curve plotted using matplotlib.

5. Results Summary
Accuracy: 97.37%

ROC AUC Score: 0.997

The model performs excellently at distinguishing malignant and benign tumors.

 Output Example

 Confusion Matrix:
[[70  1]
 [ 2 41]]

Classification Report:
              precision    recall  f1-score   support

           0       0.97      0.99      0.98        71
           1       0.98      0.95      0.96        43

    accuracy                           0.97       114
   macro avg       0.97      0.97      0.97       114
weighted avg       0.97      0.97      0.97       114
