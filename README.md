# Machine Problem 1

In this machine problem, we are going to implement two estimators: a Kalman filter and a binary LDPC decoder.
The estimation is based on belief propagation, as discussed in the following article.
 * H.-A. Loeliger. [An Introduction to Factor Graphs.](https://dx.doi.org/10.1109/MSP.2004.1267047) IEEE Signal Processing Magazine, 21(1), 28-41, Jan 2004.
Note that the factor graph structure contained in this Python file matches the structure of [24].

## Task 1

Implement a factor graph estimator for a Kalman filter applied to an AR-1 Gaussian process.

## Task 2

Implement a factor graph estimator for a binary LDPC code using the tanh method.
 * __Code__: `class CheckNodeTanh(GenericNode)`
