<h2 align="center">Comparing few classification models</h1>
<h4 align="left">Overview</h4>
<p align="left"> In this project a thorugh comparision between 5 classification models is done. The main objective of this project is to choose the best model for the dataset to properly predict the outcome variable. The five classification models used are (in order of usage):</p>
1. Linear Regression<br />
2. Logistic Regression<br />
3. K Nearest Neighbors<br />
4. Linear Discriminant Analysis<br />
5. Random Forest Classifier<br />
<p align="left"> The models are compared based on the accuracy as well as the interpretability and final model is chosen on the basis of these properties</p>
<h4 align="left"> The dataset</h4>
<p align="left">The dataset is a classification data derived from the boston house dataset. It contains 506 observations and 19 columns. Three of the columns are categorical variables, rest are quantitative variables. The outcome variable is the 'Sold' variable. The objective of the models is to predict whether a house with given independent variables will be sold within a fixed amount of time. The dataset requires preprocessing as it contains null values, correlated variables, and variables that do not contribute to the outcome variable. We'll also try to choose the model based on the inferential data obtained from it.</p>
<h4 align="left">The Language</h4>
 <p align="left">The entire code is written in python (v 3.9.4) using the scikit module in jupyter notebook. While importing the modules or any other action, the action is explained in the notebook. Scikit learn provides an easy approach to build train and use machine learning models. While it was also possible to use statsmodels for some models but it is avoided to keep uniformity throughout the code. For plotting the graphs or other kinds of plots for analysis, matplotlib and seaborn are used.</p>
 <h4 align="left">Accuracy</h4>
 <p align="left"> The accuracy is calculated by accuracy_score function of sklearn.metrics. The data is divided into two parts-train and test. The accuracy_score of models on the test set is taken as a feature to compare. Training accuracy_score is not taken as then the overfitted models would score highest.Although the highest accuracy score that was achieved is not that good, it doesn't matter as our aim is just to compare the models</p>
