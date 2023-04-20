# Employee-Satisfaction-Predictions
## Predict employee satisfaction based on personal/HR information

**Author**: Ankit Dey

### Business Problem:
The purpose of this project was to predict passenger satisfaction using personal information from corporate airline data. Company leadership can then use this model to improve passenger satisfaction by identifying key changes in company procedures that will have the largest influence on increasing passenger satisfaction.

### Data:
Data was sourced from a corporate partner of Coding Dojo. The dataset contains 22 features related to employee personal information and 20000 observations.

### Methods used:
- Data mining
- Data cleaning and processing
  - PCA
- Exploratory analyses
- ANN model built using TensorFlow and Keras
- Model evaluation based on regression metrics 

### Model Evaluation:
The final model is an ANN containing two hidden layers with ReLu activation.

This model shows an accuracy of 97%, precision of 98%, recall of 95%, and f1-score of 96%. It accurately predicts satisfaction for 97% of employees with a similar amount of false negative and false positive errors.

### Limitations and Next Steps
Although the model performs very well at predicting employee satisfaction, as an ANN it is not very transparent - this makes it difficult to extract the key pieces of personal information that showed the greatest effect on satisfaction. A simpler model, such as a decision tree, may be helpful to determine which changes are most important to improving passenger satisfaction.

### Contact


For further information, please contact **ankitkdey@gmail.com**
