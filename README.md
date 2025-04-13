# Credit Card Fraud Detection using AutoML

This project uses AutoML (PyCaret + SMOTE) to detect fraudulent credit card transactions. It focuses on precision-recall tradeoffs, explainability with SHAP, and conceptual extension toward AGI-powered fraud detection.

## Features
- AutoML-based pipeline using PyCaret
- SMOTE applied for handling class imbalance
- Precision/Recall evaluation, PR-AUC, and calibration curve
- SHAP explainability plot for model transparency
- Conceptual enhancement using Artificial General Intelligence (AGI)

## Dataset
Synthetic dataset structured with:
- TransactionID, Date, Amount, MerchantID
- TransactionType, Location, IsFraud (target)

## Run on Google Colab
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1QIp0fQ8xDp47BjMHLUWK4mbzW3QLuVpl)

## Team Members
- Tejaskumar Sanjaykumar Patel (200575242)
- Chintan Chauhan (200564227)
- Priyank Bhaveshbhai Siddhapura (200544911)
- John Hanok (200573253)

## References (APA Format)

1. Carcillo, F., Le Borgne, Y.-A., Caelen, O., Bontempi, G., & Mazzer, Y. (2019). Scarff: A scalable framework for streaming credit card fraud detection with Spark. *Information Fusion, 41*, 182–194. https://doi.org/10.1016/j.inffus.2017.09.005

2. Chawla, N. V., Bowyer, K. W., Hall, L. O., & Kegelmeyer, W. P. (2002). SMOTE: Synthetic minority over-sampling technique. *Journal of Artificial Intelligence Research, 16*, 321–357. https://doi.org/10.1613/jair.953

3. Gijsbers, P., LeDell, E., Poirier, S., Thomas, J., Bischl, B., & Vanschoren, J. (2019). An open source AutoML benchmark. *arXiv preprint arXiv:1907.00909*. https://arxiv.org/abs/1907.00909


## Version Info

- Python: 3.11
- PyCaret: 3.0.4
- pandas: 2.2.2
- sklearn: 1.3.2
- seaborn: 0.12.2
- matplotlib: 3.7.5

