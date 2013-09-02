Sharpkit.Learn - Machine Learning library for .Net (C#, F#)
==============

Sharpkit.Learn is machine learning library for .Net and mono.
It is based on Math.Net library and different state-of-the art
machine learning libraries. In particular it uses [liblinear](http://www.csie.ntu.edu.tw/~cjlin/liblinear/).

It supports both sparse and dense matrices. If you need extra
performance, you can use various BLAS providers (like MKL and cublas)
which can be plugged in into Math.Net.

Currently the library is a port of scikit-learn python library and is very
close to it's code base. But eventually the codebase may
become different from scikit learn, because the goal is to
create easy to use high-performance managed machine learning library.


What it contains now
==============
   * Linear regression
   * Logistic regression
   * Ridge regression
   * Ridge classifier
      

What it will contain soon
==============
   * SVM
   * Decision Trees
   * Random Forests
   * Nearest neighbors
   * Naive Bayes
   * Cross validation utilities
   * PCA
   * Ensemble methods

Documentation
===============
   Currently the design is very close to the Scikit-learn python library.
   You can start [there](http://scikit-learn.org/stable/documentation.html)
   I will provide basic C# and F# examples, but complete documentation requires
   a lot of time to write.


How you can help
===============
   * Use library in your projects and report issues
   * Port some scikit.learn functionality which you need
      The list is here: http://scikit-learn.org/stable/modules/classes.html#module-sklearn.svm
   * Implement some missing feature you need     
   * Perform benchmarking
   * Blob about the library.

License
===============

     Math.NET Numerics is covered under the terms of the [MIT/X11](http://mathnetnumerics.codeplex.com/license)
     Sharpkit.Learn is covered under the terms of the BSD Clause 3 license.
     Liblinear is covered under the terms of the Modified BSD License.
