### LR
```
              precision    recall  f1-score   support

      Benign       0.91      0.96      0.93      2542
    Phishing       0.93      0.83      0.88      1519

    accuracy                           0.91      4061
   macro avg       0.92      0.90      0.91      4061
weighted avg       0.91      0.91      0.91      4061
```

<p align="center">
    <img src="./figs/TFIDF/LR_CM.png" alt="LR confusion matrix"/>
</p>

### KNN
```
              precision    recall  f1-score   support

      Benign       0.83      0.98      0.90      2542
    Phishing       0.95      0.67      0.79      1519

    accuracy                           0.86      4061
   macro avg       0.89      0.82      0.84      4061
weighted avg       0.88      0.86      0.86      4061
```

<p align="center">
    <img src="./figs/TFIDF/KNN_CM.png" alt="KNN confusion matrix"/>
</p>

### RFC
```
              precision    recall  f1-score   support

      Benign       0.95      0.96      0.95      2542
    Phishing       0.93      0.91      0.92      1519

    accuracy                           0.94      4061
   macro avg       0.94      0.93      0.94      4061
weighted avg       0.94      0.94      0.94      4061
```

<p align="center">
    <img src="./figs/TFIDF/RF_CM.png" alt="RF confusion matrix"/>
</p>

### MLP
```
              precision    recall  f1-score   support

      Benign       0.94      0.96      0.95      2542
    Phishing       0.94      0.90      0.92      1519

    accuracy                           0.94      4061
   macro avg       0.94      0.93      0.93      4061
weighted avg       0.94      0.94      0.94      4061
```

<p align="center">
    <img src="./figs/TFIDF/MLP_CM.png" alt="MLP confusion matrix"/>
</p>
