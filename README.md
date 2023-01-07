# *Machine Learning Project 1-Bank Note Analysis*


![image](https://user-images.githubusercontent.com/112689649/211123066-24b84e4b-d793-45fd-a3ba-790ae738fb2f.png)



In this project, we will classify if a bank note is fake or genuine

*   Dataset link (UCI) - https://archive.ics.uci.edu/ml/datasets/banknote+authentication
*   Dataset link (Kaggle) - https://www.kaggle.com/datasets/ritesaluja/bank-note-authentication-uci-data

Data Set Information:

Data were extracted from images that were taken from genuine and forged banknote-like specimens. For digitization, an industrial camera usually used for print inspection was used. The final images have 400x 400 pixels. Due to the object lens and distance to the investigated object gray-scale pictures with a resolution of about 660 dpi were gained. Wavelet Transform tool were used to extract features from images.

Attribute Information:

1. variance of Wavelet Transformed image (continuous)
2. skewness of Wavelet Transformed image (continuous)
3. curtosis of Wavelet Transformed image (continuous)
4. entropy of image (continuous)
5. class (integer)

Data Set Characteristics : Multivariate

Associated Tasks : Classification

-----------------------------------------------------------------------------------------------------------------------------------

*   In the dataset, we have 1372 rows and 5 columns.

*   Splitting data as training and testing sets.

*   We will perform some fundamental preprocessing steps on the dataset.

*   We will do data visualization to get a clarity on what we are doing.

*   We will be using different algorithms such as :
    * Logistic Regression
    * Support Vector Machine
    * Random Forest Classifier
    * K Nearest Classifier
    * Multilayer Perceptron
    
*   After Building the Algos, we will build a cross validation score along with a confusion matrix and Accuracy score to check how well our model is performing.


We are using Jupyter Notebook for working with the data for this project --


