## Analysis of Deep Learning Models and Hurdle Frameworks for CRISPR-Cas9 Cleavage Rate Prediction

University of Oxford Master's Project

Score: 75/100 (Distinction)

## Abstract
This thesis introduces a novel application of the hurdle model architecture to predict CRISPR-Cas9 cleavage rates under conditions of extreme class imbalance. Traditional machine learning models often fail to generalize on synthetic datasets in which over 90% of targets exhibit zero cleavage. However, by separating the prediction of cleavage occurrence (a classification task) from the prediction of cleavage magnitude (a regression task), the hurdle model effectively addresses the zero-inflated nature of the data to yield substantial performance improvements.

We evaluate a range of deep learning architectures, including FNNs, CNNs, LSTMs, as well as conventional tree-based models, employed as both classifiers and regressors within the hurdle framework. The most effective configuration combines an LSTM classifier with a Gradient Boosting Regressor, achieving a Spearman rank correlation of 0.881. A stacking ensemble of 25 such models further enhances performance to 0.893.

An ablation study highlights the critical role of thresholding in the hurdle model, while SHAP analysis identifies the individual models that most influence the ensemble's predictions.

