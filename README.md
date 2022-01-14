# Accuracy-metrics
After model fitting it is usually of interest to assess how well it can predict data which it has not seen before hand(during training).
By comparing model's predictions and the actual data.
## Accuracy
This is the ratio of correct predictions to total predictions.

```r
accuracy = correct_pred / total_pred
```

## Confusion Matrix
A Confusion matrix is a N x N matrix that is used to assess the effectiveness of a classification model, where N is the number of target classes. The matrix compares the actual target values to the machine learning model's predictions.
![confmat](https://github.com/SirWilliam254/Accuracy-metrics/blob/main/confusionMat.jpg)

## F1 score

```r
F1 score is defined as the harmonic mean between precision and recall. It is used as a statistical measure to rate performance.
```
its best value is at 1 and worst score at 0

```r
F1 = 2 * (precision * recall) / (precision + recall)
```

## Precision

```r
precision = True Positives / (True Positives + False Positives)
 ```
 this number tells us the percentage of the correctness of a prediction given a certain model.
## Recall

```r
Recall = TP/(TP + FN)
//TP is true positive and FN false negative
```
The number of false negatives introduced into the prediction mix is referred to as recall. When a false negative is anticipated, the recall rate is punished.

## rmse
```r
Root mean square error of the formula:
sqrt(mean((actual - predicted)^2))
```
The root mean square error is a metric that informs us the average distance between the model's predicted values and the actual values in the dataset.

## MSE

```r
Mean Square Error:

mean(model_sums$residuals^2) or rather
mean((actual - predicted)^2)
```
For MSE the average squared difference between the observed and predicted values is calculated. When there is no error in a model, the MSE is 0. As model inaccuracy rises, so does its value.

## MAE
```r
mean absolute error is the name
absolute error = |Actual Value - Predicted Value|
MAE = Average of All absolute errors
```
this is the average of all absolute errors
## R-squared

## MAPE

## MPE
