## Sanger Anomaly Detection Workshop Code

This repository contains code used for the unsupervised learning section of the
machine learning workshop given to the Systems group at Sanger that I helped to run.

The idea is based on Chapter 4, *More Complex, Adaptive Models* from
[Practical Machine Learning](https://www.safaribooksonline.com/library/view/practical-machine-learning/9781491914151/ch04.html)
by Ted Dunning and Ellen Friedman.

* `Unsupervised Learning.ipynb` is an IPython notebook demonstrating a simple example of unsupervised learning: time-series anomaly detection.
* `a02.dat` is a set of EKG data from PhysioNet used to demonstrate the
  algorithms.
* `ekg_data.py` is a module for reading the EKG data.
* `learn_utils.py` is a collection of helper functions developed in the
  notebook, saved as a module for reuse.
* `learn.py` is a complete listing for the code developed in the notebook.

### Requirements

Python is required, along with the following modules:
* NumPy
* matplotlib
* scikit-learn

If you're on Ubuntu:
```
$ sudo apt-get install python-numpy python-matplotlib python-sklearn
```
Or on any system with pip:
```
$ pip install numpy matplotlib scikit-learn
```
