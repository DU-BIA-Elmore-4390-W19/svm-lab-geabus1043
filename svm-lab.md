Untitled
================
Jason Carlson
3/5/2019

1.  This question refers to Chapter 9 Problem 8 beginning on page 371 in the text.

    1.  Create a training sample that has roughly 80% of the observations. Use `set.seed(19823)`.
    2.  Use the `kernlab` package to fit a support vector classifier to the training data using `C = 0.01`.
    3.  Compute the confusion matrix for the training data. Report the overall error rates, sensitivity, and specificity.
    4.  Construct the ROC curve.
    5.  Use the `train` function from the `caret` package to find an optimal cost parameter (`C`) in the range 0.01 to 10. Use `seq(0.01, 10, len = 20)`.
    6.  Compute the training and test classification error.
    7.  Repeat (b) - (d) using an SVM with a polynomial kernel with degree 2.
    8.  Which method would you choose?
    9.  Repeat (b) - (d) using an SVM with a radial basis kernel. Train it.
    10. Using the best models from LDA, SVC, SVM (poly), and SVM (radial), compute the test error.
    11. Which method would you choose?

2.  Train one of the SVM models using a single core, 2 cores, and 4 cores. Compare the speedup (if any).
3.  You might want to look at `rbenchmark` or `microbenchmark` packages for timing.
