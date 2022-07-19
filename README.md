# credit_risk_analysis
## Overview
The purpose of this analysis is to employ different techinques to train and evaluate models with unbalanced classes. These techniques will be used to evaluate the performance of the different models and help make a recommendation on whether the models should be used to help predict credit risk.

## Results

### 1. Naive Random Oversampling
![image](report_naive.png)
![image](matrix_naive.png)
![image](balanced_naive.png)
- The balanced accuracy of the naive random oversampling is 64.6%
- the high risk percentage is 1%
- Sensitivity is 61%
- F1 is 2%
- Precision is 99% with sensitivity of 68%

### 2. SMOTE Oversampling
![image](smote_report.png)
![image](smote_matrix.png)
![image](smote_balanced.png)
- The balanced accuracy of SMOTE Oversampling is 62.3%
- The high risk percentage is 1%
- Sensitivity is 61%
- F1 is 2%
- Precision is 99% with sensitivity of 64%

### 3. Undersampling
![image](report_under.png)
![image](matrix_under.png)
![image](balanced_under.png)
- The balanced accuracy of Undersampling Oversampling is 52.9%
- The high risk percentage is 1%
- Sensitivity is 61%
- F1 is 1%
- Precision is 99% with sensitivity of 45%

### 4. Combination Sampling
![image](report_combo.png)
![image](matrix_combo.png)
![image](balanced_combo.png)
- The balanced accuracy of Combination Sampling Oversampling is 64%
- The high risk percentage is 1%
- Sensitivity is 70%
- F1 is 2%
- Precision is 99% with sensitivity of 58%

### 5. Balanced Random Forest Classifier
![image](report_ensemble.png)
![image](matrix_ensemble.png)
![image](balanced_ensemble.png)
- The balanced accuracy of Balanced Random Forest Classifier Oversampling is 78.8%
- The high risk percentage is 4%
- Sensitivity is 67%
- F1 is 7%
- Precision is 99% with sensitivity of 91%

### 6. Easy Ensemble AdaBoost Classifier
![image](report_easy.png)
![image](matrix_easy.png)
- The high risk percentage is 1%
- Sensitivity is 67%
- F1 is 7%
- Precision is 99% with sensitivity of 91%

## Sumary
Overall, most of the models show weak precision in determing credit risk. The low precision shows several credits being falsely detected as high risk, which would affect a bank's strategy and could affect revenue. It would not be recommended that the bank use these six models to help predict credit risk.
