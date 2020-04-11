# data analysis process

* check dataset shape
* any missing values
  * remove (rows or columns)
  * impute or add new label 'missing' (0, 1)
    * mean, median, mode (categorical data)
    * 0, a very small/large number to differentiate missing values from other values
    * predict using other columns and a supervised model
    * find similar rows and fill with their values (knn)
  * work around
* categorical columns
* any unexpected data types (numbers showing as strings)
* build exploratory plots, like bar charts, histograms, scatterplots
* [standardize/normalize the data](https://scikit-learn.org/stable/modules/preprocessing.html)
  * **scale, transform, normalize** The sklearn.preprocessing package provides several common utility functions and transformer classes to change raw feature vectors into a representation that is more suitable for the downstream estimators.
In general, learning algorithms benefit from standardization of the data set. Standardization of datasets is a common requirement for many machine learning estimators implemented in scikit-learn; they might behave badly if the individual features do not more or less look like standard normally distributed data: Gaussian with zero mean and unit variance.



1. instantiate
2. fitting
3. predict
4. score

## Two techniques for deploying your results include:
* Automated techniques built into computer systems or across the web. You will do this later in this program!
* Communicate results with text, images, slides, dashboards, or other presentation methods to company stakeholders.
