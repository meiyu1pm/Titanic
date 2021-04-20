# Titanic
Titanic project for kaggle competition

- by Yu Mei
- In this project, I used the Bayes Theorem to predict the survive of Titanic passengers. Because both categories and continuous variable in data structure.
- Also, I tried logistic regression, but the accuracy was not as good as Bayes model.
- I combine the siblings and parents columns into one column, because I believe they have relationship.
- In this project, the probability need to preprocess with Laplace smoothing. The predicting accuracy is about 78%
Also, I use built in function GaussianNB to predict and compared the effective to my algorithm.
