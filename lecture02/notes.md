# How they organize the image classification problem? 

## Image classification-related Challenges: 

---

## Questions:

1. Nearest Neighbor classifier: with N examples, how fast will the training and prediction be?

Train O(1), predict O(N)

---

Distance metrics: With different distance metrics we can generalize **kNN classifier** to many data. 

Hyperparameters: 1. Distance metric; 2. number *k*

They are very problem-dependent. 

1. L1 (Manhattan)

2. L2 (Euclidean)

---

Setting parameters -> Cross validation

Idea #1: get the best accuracy

---

Why not kNN on image classification?

1. distance between pixels are not informative. 

2. slow to predict

3. curse of dimensionality 

4. Boxed, shifted, tinted 

---

## CIFAR-10 classification 

Linear Classifier: 

Template matching if there is only a linear classifier 

---

What is **hyperparameter tuning**? Hyper-parameters are not the parameters a algorithm learning, but setting by users. 

What is **validation loss** ?  
