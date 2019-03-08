# Tese-HellenGeremias

This repository contains R codes elaborated for the analyzes presented in my thesis entitled
"Comparison of Machine Learning algorithms performance in predictive analyzes in public health and medicine" (http://www.teses.usp.br/teses/disponiveis/6/6141/tde-09102018-132826/pt-br.php)

1) The first manuscript is a tutorial for the Machine Learning use in health research. As an example we predicted death up to 5 years
for elderly participants in the study “Saúde, Bem-estar e Envelhecimento”.
Five algorithms were applied: logistic regression with and without regularization, neural networks, 
gradient boosted trees and random forest; hyperparameters were optimized by 10-fold cross validation.

2) The second manuscript aimed to predict the risk of quality-adjusted life year equal or less than 30 days in oncologic patients 
admitted to the Intensive Care Unit. Six algorithms (logistic regression with and without regularization, neural networks, 
basic decision trees, gradient boosted trees and random forest)
were used in conjunction with nested cross validation (leave-one-out cross validation for the outer loop 
and 10-fold cross validation for the inner loop).

3) The third manuscript aimed to predict life expectancy at birth of Brazilian municipalities with more than 10,000 inhabitants 
using socioeconomic and demographic characteristics. For this analysis we used nested cross validation 
(10-fold cross validation both for outer and inner loop) and the Super Learner algorithm.
