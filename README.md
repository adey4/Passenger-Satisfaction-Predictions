# Passenger-Satisfaction-Predictions
## Predict passenger satisfaction based on airline company surveys

**Author**: Ankit Dey

### About:
The purpose of this project was to predict passenger satisfaction using personal information from corporate airline data. Company leadership can then use this model to improve company procedures through the identification of key factors that will have the largest influence on increasing passenger satisfaction.

### Data:
Data was sourced from a corporate partner of Coding Dojo. The dataset contains 22 features related to employee personal information and 20000 observations.

### Methods used:
- Data mining
- Data cleaning and processing
  - PCA
- Exploratory analyses
- ANN model built using TensorFlow and Keras
- Model evaluation based on classification metrics 

### Model Evaluation:
#### Metrics
<img src="https://github.com/adey4/Employee-Satisfaction-Predictions/blob/main/loss.png" width=75% height=50%>
<img src="https://github.com/adey4/Employee-Satisfaction-Predictions/blob/main/accuracy.png" width=500 height=333>
<img src="https://github.com/adey4/Employee-Satisfaction-Predictions/blob/main/recall.png" width=500 height=333>
<img src="https://github.com/adey4/Employee-Satisfaction-Predictions/blob/main/precision.png" width=500 height=333>

#### Confusion Matrix
<img src="https://github.com/adey4/Employee-Satisfaction-Predictions/blob/main/cfmat.png" width=450 height=333>

The final model is an ANN containing two hidden layers with ReLu activation.

This model shows an accuracy of 97%, precision of 98%, recall of 95%, and f1-score of 96%, accurately predicting satisfaction for 97% of employees with a similar amount of false negative and false positive errors (ROC AUC Score = 0.99).

### Limitations and Next Steps
Although the model performs very well at predicting passenger satisfaction, as an ANN it is not very transparent - this makes it difficult to extract the key pieces of personal information that showed the greatest effect on satisfaction. A simpler model, such as a decision tree, may be helpful to determine which factors are most important to improving passenger satisfaction.

### Contact


For further information, please contact **ankitkdey@gmail.com**
