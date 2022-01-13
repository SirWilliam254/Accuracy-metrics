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


## Recall

## rmse

## MSE

## MAE

## R-squared

## MAPE

## MPE
