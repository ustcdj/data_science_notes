# data analysis process

* check dataset shape
* any missing values
  * remove (rows or columns)
  * impute or add new label 'missing' (0, 1)
    * mean, median, mode
    * predict using other columns and a supervised model
    * find similar rows and fill with their values
  * work around
* categorical columns
* any unexpected data types (numbers showing as strings)
* build exploratory plots, like bar charts, histograms, scatterplots
* standardize/normalize the data

1. instantiate
2. fitting
3. predict
4. score
