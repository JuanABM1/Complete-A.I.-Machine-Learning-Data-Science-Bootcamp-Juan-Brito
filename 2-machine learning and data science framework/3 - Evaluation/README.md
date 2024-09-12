# Evaluation

There are different evaluation metrics for classification, regression and recommendation problems. Which one you choose will depend on your goal. There are differents types of metrics depending in the classification of the problem

---

## Metrics for classification problems

### Precision 

What proportion of positive predictions were actually correct? A model that produces no false positives has a precision of 1.0.

### Recall 

What proportion of actual positives were predicted correctly? A model that produces no false negatives has a recall of 1.0.

### Acurracy

A combination of precision and recall. The closer to 1.0, the better.

---

## Metrics for Regression problems

### Mean absolute error (MAE)

The average difference between your model's predictions and the actual numbers.

### Root mean square error (RMSE) 

The square root of the average of squared differences between your model's predictions and the actual numbers.

--- 

## Metrics for recomendation problems

### Precision up to k 

Same as regular precision, however, you choose the cutoff, k. For example, precision at 5, means we only care about the top 5 recommendations. You may have 10,000 products. But you can’t recommend them all to your customers.




