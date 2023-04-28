# Machine Learning Model for Phishing Classification


## Description
This project presents the implementation of a Machine Learning model using Logistic Regression for the classification of texts that present phishing features. The objective is to identify and classify emails or text messages as phishing or non-phishing. 
Here we present the implementation of the Logistic Regression based model along with data preprocessing to evaluate the performance of the machine learning model. 

## Dataset
The dataset contains 5971 text messages labeled as legitimate (ham), spam or smishing. It includes 489 spam messages, 638 smishing messages and 4844 ham messages. The data can be used for deep learning or additional attribute extraction. It also contains attributes extracted from malicious messages that can be used for classification of messages as malicious or legitimate [[1]](https://https://data.mendeley.com/datasets/f45bkkt8pr/1).


## Results
The following is the classification report obtained after running the model.

```
              precision    recall  f1-score   support

         ham       0.99      0.98      0.98       948
    smishing       0.88      0.85      0.86       146
        spam       0.76      0.82      0.79       100

    accuracy                           0.95      1194
   macro avg       0.87      0.88      0.88      1194
weighted avg       0.95      0.95      0.95      1194
```

This is a classification report showing various evaluation metrics for a three-class classification model: ham (legitimate mail), smishing and spam. The metrics include precision, recall and f1-score for each class, as well as the overall accuracy of the model.

Accuracy measures the proportion of true positives among all positive predictions. In this case, the precision for the ham class is 0.99, meaning that 99% of the e-mails classified as ham are actually ham.

The recall measures the proportion of true positives among all true positive cases. In this case, the recall for the ham class is 0.98, meaning that 98% of all true ham emails were correctly classified as ham.

The f1-score is a measure that combines precision and recall into one value. It is calculated as the harmonic mean of precision and recall. In this case, the f1-score for the ham class is 0.98.

The overall accuracy of the model is 0.95, which means that 95% of all predictions are correct.


## References
[1] mishra, sandhya; Soni, Devpriya (2022), *“SMS PHISHING DATASET FOR MACHINE LEARNING AND PATTERN RECOGNITION”*, Mendeley Data, V1, doi: 10.17632/f45bkkt8pr.1
