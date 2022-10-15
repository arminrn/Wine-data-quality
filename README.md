# Wine-data-quality

# Description

These data are the results of a chemical analysis of wines grown in the same region in Italy but derived from three different cultivars. The analysis determined the quantities of 13 constituents found in each of the three types of wines. So it contains 13 feature and 178 instances, in order to classify the records, we need to use classification models. In this project we will use 4 different algorithm. KNN, MDC, SVM, and LG will be implement and at the end the results will be compared.

# Libraries

Pandas

Numpy

Seaborn

matplotlib

sklearn

# Files

Wine.data: database that has been used for this project
Wine-data.ipyt: code that is wrriten for this project
# Results

LG has the most accurate prediction, and then SVM, MDC, and KNN are in seond, third, and forth levels. However, all the algorithms have acceptable results, and without using other features we are able to predict the model. 
When we add all the features to predict the data MDC works more accurate, LG and SVM are in other levels, and KNN stand at the final level. 
.The most obvious result that we can conclude from the implementation of the algorithms is, the more feature added, the more accurate the model will be. Besides, we can conclude there is no any best algorithm in classification, in fact it depends on the data and also the how many features are extracted, so the best way for choosing an algorithm is trying some of them, and compare them together.
