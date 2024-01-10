<img src="risk.jpg">
<h1>Credit Default Risk Analysis</h1>

In this project, machine learning algorithms were compared for credit default risk assessment using a dataset of 32,581 observations and 12 variables. Key findings include:

- **Logistic Regression:**
  - Accuracy: 69.51%
  - AUC: 0.5030

- **Linear Discriminant Analysis (LDA):**
  - Accuracy: 86.69%
  - AUC: 0.8669

- **Ridge Regression:**
  - Accuracy: 86.61%
  - AUC: 0.8689

- **Classification Tree:**
  - Accuracy: 92.18%
  - AUC: 0.8237

**Key Insights:**
- The Classification Tree had the highest accuracy, but struggled to distinguish positive and negative classes.
- Ridge Regression demonstrated superior performance with a higher AUC value.
- The root node in the Classification Tree was the loan-to-income proportion, emphasizing its importance.
- Ridge Regression is recommended for risk classification, especially in diverse risk scenarios.

## Conclusion

Ridge Regression proves to be a safer choice for credit default risk classification due to its superior AUC value.
