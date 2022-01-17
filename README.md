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

```r
R2= 1- SSres / SStot

where,
SSres: sum of squares of the residual errors.
SStot: represents the total sum of the errors.
```

R-squared (R2) is a statistical metric that quantifies the proportion of the variation explained by an independent variable or variables in a regression model for a dependent variable. Whereas correlation describes the strength of the link between an independent and dependent variable, R-squared explains how well one variable's variation explains the variance of the other. So, if a model's R2 is 0.50, then the model's inputs can explain roughly half of the observed variance.

## MAPE
```html
MAPE stands for Mean Absolute Percent Error
```
```r
MAPE = (1/n) * Σ(|Original – Predicted| / |Original|) * 100


n – is the sample size

actual – is the actual data value

forecast – is the forecasted data value
```

MAPE is widely utilized since it is simple to comprehend and explain. A MAPE score of 9.5 percent, for example, indicates that the average difference between the predicted and actual value is 9.5 percent.

The lower the MAPE number, the better a model can estimate values. A model with a MAPE of 3%, for example, is more accurate than a model with a MAPE of 13%.

## MPE
