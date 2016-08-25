# learning-from-imbalanced-classes

This repo corresponds to a blog post I wrote discussing how to learn from data
with imbalanced classes.  The blog post is here: http://www.svds.com/learning-imbalanced-classes/.  In this directory you'll
find two Python Jupyter notebooks illustrating two
points made in that blog post.

`Gaussians.ipynb` is an interactive notebook that allows you to play with
varied sampling from two Gaussian distributions to see what logistic
regression does with the points as the mixtures are varied.

`ImbalancedClasses.ipynb` illustrates a method called **blagging** (basically,
downsampled bagging) on a domain called
[Glass](https://archive.ics.uci.edu/ml/datasets/Glass+Identification) from the
UCI Repository.  It goes through steadily more imbalanced versions of the
domain, testing different algorithms and showing the results.
