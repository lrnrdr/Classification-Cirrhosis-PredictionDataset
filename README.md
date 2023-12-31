# Cirrhosis Predictions

## Analyzing various attributes contributing to Cirrhosis

Author: Loraine Rodriguez

___
## **Business Problem**

To assist a drug company to evaluate Drug D- penicillamine and its effects on different known contributors to Cirrhosis.   The goal of this is to help the drug company understand the effects and know how to properly market the drug, if it is shown in the data, that it prevents Cirrhosis. 

## **Data**

Cirrhosis Prediction Dataset: 
https://www.kaggle.com/datasets/fedesoriano/cirrhosis-prediction-dataset
___

## **Methods**
With the data provided, we were able to create various different machine learning models. 
___

## **Comparision of 2 Explanatory Visuals**
Visual #1 - Using Barplot to compare choleterol to Stages (For Drug)
Visual #2-  Comparing Subplots of Cholesterol vs Bilirubin (For Drug)
___


## Visual #1
![image](https://github.com/lrnrdr/Classification-Cirrhosis-PredictionDataset/assets/138408700/e6c733fc-19ba-4680-8461-7d5ab53c343b)


All stages had high cholesterol of >200 mg/dl while on Drug D.   The placebos and D-penicillamine performed neck and neck through most of the stages with an exception to stage 1 which D-penicillamine had a Cholesterol of ~300 mg/dl and placebo had just under 200 mg/dl.  Given that the placebo's performed so close to D-penicillamine, it doesn't seem as if this drug was effective when evaluating Cholestrol and the stages.

  
## Visual #2

![image](https://github.com/lrnrdr/Classification-Cirrhosis-PredictionDataset/assets/138408700/2eba0506-daa3-422a-b1e0-80139a780981)


There isn't a big difference between Cholesterol in both D-penicillamine and the Placebo, so I don't think the drug effects cholesterol.   I can see that the cholestrol average is over 200, so that is high cholestrol.   

For Bilirubin there is a slight difference between both D-penicillamine and the Placebo levels.  The ones on D-penicillamine had lower Bilirubin vs the ones taking the placebo, but its slight.

___
## Metrics for best model

### PCA Model Metrics
![image](https://github.com/lrnrdr/Classification-Cirrhosis-PredictionDataset/assets/138408700/d2682d7a-d9be-4634-9171-c3e5ab2f9bf9)


The PCA model lowered the Type II (False negatives) which is the best metric to consider when dealing with a medicial condition/disease.  We want to have the least amount possible of Fales Negatives because this means patients would be told they don't have the desease and they really do, so the lower the better.  The PCA Model had Type II errors of 28%, verses the other models which had a higher chance of False Negatives.



