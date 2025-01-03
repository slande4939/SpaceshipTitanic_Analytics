# Predictive Analytics: Understanding Transportations in Spaceship Titanic

I.	Problem Statement/Executive Summary

This project centers around the premise that an interstellar passenger liner—the Spaceship Titanic—collided with a spacetime anomaly mid-voyage, causing almost half of its 13,000 passengers to be transported to an alternate dimension. The training dataset contains data about each passenger including their cabin, VIP status, home planet, and other explanatory variables. The target variable “Transported?” indicates whether a passenger had the misfortune to be transported. The goal of this project is to train several models which can accurately predict whether a passenger will be transported or remain safely on board.
We present four models—Logistic Regression, Random Forest, Support Vector Machine (“SVM”), and Neural Network—each using a cross-validation design. Each model’s performance is compared in Table 1 below. “Accuracy on Training Data” indicates how well a model identifies trends in the data used to train it. “Accuracy on Testing Data” better shows how well the model’s predictions will generalize to data the model may encounter in the future. We recommend the SVM classifier for making future predictions, due to its demonstrated ability to generalize to the test data best.

