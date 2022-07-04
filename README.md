# Credit_Risk_Analysis
Challenge17

Introduction
Purpose
The purpose of this exercise is to determine of the 6 Machine Learning Models available, which is the vest model to determine credit card risk for the credit card credit dataset from LendingClub. 

Results

Accuracy Score of 6 Machine Learning Models
Not all 6 machine learning models produced the same accuracy score. The Undersampling module was the least accurate being furthest from a score of 1.0 while Easy Ensemble AdaBoost Classifier was the most accurate being the closest to a score of 1.0
-Naive Random Oversampling produced the accuracy score of 0.6370547638903997.
-SMOTE Oversampling produced the accuracy score of 0.6252321613465963.
-Undersampling  produced the accuracy score of 0.5293318990697431.
-Combination (Over and Under) Sampling produced the accuracy score of 0.6265999492367381.
-Ensemble Learners produced an accuracy score of 0.787767265306695 which is slightly more accurate than the previous models.
-Easy Ensemble AdaBoost Classifier produced an accuracy score of 0.925427358175101 which is the most accurate of all 6 models.

Precision scores of 6 Machine Learning Models
All models produced the same average/total precision of 0.99, despite each having differing high_risk and low_risk precisions.
-Naive Random Oversampling produced a high_risk precision of 0.01 and a low_risk precision of 1.00 (Naive_Random_Oversampling.JPG file).
-SMOTE Oversampling produced  a high_risk precision of 0.01 and a low_risk precision of 1.00 (SMOTE_Oversampling.JPG file).
-Undersampling  produced a high_risk precision of 0.01 and a low_risk precision of 1.00 (Undersampling.JPG file).
-Combination (Over and Under) Sampling produced a high_risk precision of 0.01 and a low_risk precision of 1.00 (Combination_Over_and_Under_Sampling.JPEG file).
-Ensemble Learners produced a high_risk precision of 0.04 and a low_risk precision of 1.00 (Ensemble_Learners.JPG).
-Easy Ensemble AdaBoost Classifier produced a high_risk precision of 0.07 and a low_risk precision of 1.00 (Easy_Ensemble_AdaBoost_Classifier.JPG file).

Recall Scores of 6 Learning Machine Models
Model Undersampling with the lowest recall score has the most false negatives while Easy Ensemble AdaBoost Classifier with the highest recall score has the least amount of false negatives.
-Naive Random Oversampling produced a recall average / total score of 0.66 (Naive_Random_Oversampling.JPG file).
-SMOTE Oversampling produced a produced a recall average / total score of 0.65 (SMOTE_Oversampling.JPG file).
-Undersampling  produced a recall average / total score of 0.45 (Undersampling.JPG).
-Combination (Over and Under) Sampling produced a recall average / total score of 0.55 (Combination_Over_and_Under_Sampling.JPG file).
-Ensemble Learners produced a recall average / total score of 0.91(Ensemble_Learners.JPG file).
-Easy Ensemble AdaBoost Classifier produced a recall average / total score of 0.94 (Easy_Ensemble_AdaBoost_Classifier.JPG file).


Summary
Utilize Easy Ensemble AdaBoost Classifier
Easy Ensemble AdaBoost Classifier  is the best recommended model to be utilized to predict credit card risk.  It is the most accurate, precise, and has the best recall (lowest amount of false negatives) of the 6 models.  Each score is very close to the desired 1.0: 0.93, 0.99, and 0.94 respectively. It would be difficult to find a better fit.  Ensemble Learners is a close second being the model with the second most accurate, precise, and best recall exhibiting model with precision and recall very close to the first model, but its weakness lies with the accuracy score of 0.79.  The other four models are not a good fit for determining credit risk despite their equal average/total precision scores of 0.99.  Each had significantly more false negatives per their recall scores in the low 0.45 - 0.66. Their accuracy scores also were low 0.52 - 0.64.  The worst model appears to be the Undersampling with the lowest accuracy and lowest recall scores.




