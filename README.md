# Diabetes-Diagnosis-Prediction-Machine-Learning
Using appropriate machine learning algorithm/model to  demonstrate  how machine learning can be used for diseases diagnoses
To develop, implement and compare four supervised machine-learning classification algorithms for predicting diabetes from patient medical , demographic measurements and evaluate their ability to identify records labelled as diabetic.
# Problem Statement
Diabetes risk assessment uses multiple patient measurements. This project explores whether supervised machine-learning algorithms can learn patterns from a labelled dataset and classify records into the dataset's two outcome categories. The project compares several algorithms rather than assuming one method is best.
#Conclusion, limitations and recommendations
#Conclusion template
After running the notebook, insert the actual selected candidate and the actual metric values from your outputs. State whether the candidate performed better than the majority-class baseline and discuss both recall and precision 
# Limitations
1. The dataset is relatively small and may represent a narrow population; results may not generalize to other populations.
2. Several measurements contain zero-coded missing values. Median imputation is a practical baseline but it does not recover the missing clinical measurements.
3. Only four baseline model configurations are compared. Hyperparameter tuning and feature-selection experiments could change the ranking.
4. A held-out test result is not external clinical validation.
5. Model-estimated probabilities are not calibrated clinical risk estimates unless calibration and clinical validation are specifically performed.
6. The project is not approved or intended for patient diagnosis, screening, triage or treatment decisions.
# Recommendations for future work
- Verify the dataset source, documentation, target labels and missing-value conventions.
- Compare models with and without highly incomplete features such as Insulin and SkinThickness.
- Tune hyperparameters using training-only cross-validation.
- Consider calibration and decision-threshold analysis using validation data, with an explicit discussion of the trade-off between sensitivity and false positives.
- Seek representative, ethically collected, de-identified local data and conduct independent validation with clinical and regulatory oversight before any real-world use.
# Tools Used
