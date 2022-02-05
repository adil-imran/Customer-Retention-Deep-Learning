# Customer-Retention-Deep-Learning
- Dataset is about bank customers in which we evaluate the customers retaining prediction.
- We will measure why customers are leaving.
- We will build a deep learning model to predict the retention
- At the end we use precision,recall, f1-score to measure the performance of our model.
# Bulit a Model by using Tensorflow
- Used RELU and Softmax as an activation
- Choose optimizers as Adam and loss as binary_crossentropy
- We tried 10 epochs on model training
- Model secued 85% performance.
# Conclusion
## Truth
- 1552 times found correct and 55 times uncorrect at 0 which is 97% we can see on Recall 0
- 144 times found correct and 249 times uncorrect at 1 which is 37% we can see on Recall 1

## Predicted
- 1552 times found correct and 249 times uncorrect at 0 which is 86% we can see on Precision 0
- 144 times found correct and 55 times uncorrect at 1 which is 72% we can see on Precision 1
