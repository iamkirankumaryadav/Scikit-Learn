# Logistic Regression

### Classification

Problems with Discrete and Finite Output called **Classes** or **Categories**

### Types of Classification

1. Binary | Binomial | Dichotomous (Exactly Two | 0 or 1 | True or False | Positive or Negative)
2. Multiclass | Multinomial (Three or more classes of Outputs to Choose from)

### When do you Need Classification?
1. Spam Emails
2. Medical Applications 
3. **Biological** Classification
4. Credit Scoring

### Sigmoid Function (S Shaped Curve)
**Sigmoid** Function has values very close to either **0** or **1**

![Sigmoid](Image/SigmoidFunction.png) 

### Natural Logarithm Function 
**Logarithm** Function has values between 0 and 1

![Logarithm](Image/LogFunction.png) 

### Classification Performance

![Confusion Matrix](ConfusionMatrix.jpg)

1. True Positive : Correctly Predicted Positives 
2. True Negative : Correctly Predicted Negatives
3. False Positive : Incorrectly Predicted Positive (**Type I** Error | Accept **NULL** Hypothesis)
4. False Negative : Incorrectly Predicted Negative (**Type II** Error | Do not Accept **NULL** Hypothesis)

Positive Predictive Value : TP / TP + FP

Negative Predictive Value : TN / TN + FN

**Recall** | True Positive Rate (**TPR**) | **Sensitivity** : TP / TP + FN

**Recall** | True Negative Rate (**TNR**) | **Specificity** : TN / FP + TN
