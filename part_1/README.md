# Part 1 (weeks 1-2): Foundations and the Full Workflow

These two weeks are all about learning the basics. At the end of those I should have a basic intuition of core concepts of machine learning, have a functionning setup on my desktop and explored basic concepts in practice.

The details of what I will be doing these comming days are described below.

## Day 1: Setup and intuition

- Watch 3Blue1Brown chapters 1–2. Chapters 3–4 can wait a few days, until you’ve seen gradient descent on simpler models.
- Set up Google Colab. It runs in the browser with nothing to install, and NumPy, pandas and scikit-learn come preinstalled.
- If your Python is rusty, do Kaggle Learn’s short Python and Pandas courses first. They take a few hours each.

## Days 2–7: Core concepts

- Work through Course 1 of Andrew Ng’s Machine Learning Specialization, “Supervised Machine Learning: Regression and Classification,” which you can audit for free. It covers exactly what weeks 1–2 need: linear regression, cost functions, gradient descent, logistic regression, overfitting and regularization.
- When a concept doesn’t click, look up the StatQuest video on it. He’s particularly good on gradient descent, logistic regression and bias vs. variance.
- Watch 3Blue1Brown chapters 3–4 once you reach gradient descent in the course. They’ll make much more sense at that point.

## Days 3–7, alongside the course: Build from scratch

- Implement linear regression with gradient descent in plain NumPy on a small dataset, such as house size vs. price. Plot the cost going down over iterations.
- Break it on purpose. Try a learning rate that’s too high (the cost explodes) and one that’s too low (it barely moves). Then try unscaled features and watch convergence slow down.
- Extend it to logistic regression on a simple binary classification problem.
- Check that your results match scikit-learn’s LinearRegression and LogisticRegression.

## Week 2: The practical workflow

- Do Kaggle Learn’s Intro to Machine Learning and Intermediate Machine Learning. They’re short and hands-on, and they teach train/validation splits, missing values, categorical features, pipelines and data leakage.
- Then tackle Kaggle’s Titanic competition from start to finish. Explore the data, build a dumb baseline (for example, “everyone dies,” or “women survive”), then logistic regression, and submit. Write down a few sentences about what improved your score and what didn’t.



