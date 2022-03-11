# COVID-19-stance-classification
This machine learning task is aimed to develop a text classifier that determines whether a given textual comment expresses an opinion that is positive or negative 
towards COVID-19 vaccination.

The first part of this project deals with data annotation and is solved by collecting comments in English relating to COVID-19 vaccination from social media or the 
comment fields from online articles. The comments collected express either a pro- or anti-vaccination stance hence create a balanced dataset. These annotations are 
validated by other people and hence there are multiple rounds of annotations for each comment.

The dataset would look like this:

<img width="543" alt="Screenshot 2022-03-11 at 11 26 43 AM" src="https://user-images.githubusercontent.com/101395346/157849675-bf7ab0f6-c6a2-4d67-a89a-15ea250ba242.png">


The second task of this project to implement a classifier that determines whether a given comment expresses a pro-vaccination or anti-vaccination stance. This is 
done using supervised learning methods using different classification algorithms and compare the results. Text classification being one of the most prominent 
challenging tasks in the field of machine learning deals with the categorization of text documents into different classes. This project involved building a binary 
classification model for comments and opinions on COVID-19 vaccination. Various pre-processing techniques are used to extract the essential words and vectorize the 
text. Finally, classification is performed on the labelled comments being either pro-vaccination or anti-vaccination. The data is evaluated and compared on 4 
different classifiers namely Bernoulli Naive Bayes Classifier, Support Vector Machine, Logistic Regression and Stochastic Gradient Descent classifier.

The results of all the classifier algorithms performed on the training set is given as follows:

<img width="376" alt="Screenshot 2022-03-11 at 11 32 37 AM" src="https://user-images.githubusercontent.com/101395346/157850779-020dfaa3-df2d-49cc-82ea-99392ed9e8e6.png">


Hence, the bernoulli naive bayes classifier is used for predicting results on the final testing set and determine the accuracy using the same evaluation measures. 
By predicting on the test set, the model gives 90% accuracy. The classification report looks like the follows:

<img width="384" alt="Screenshot 2022-03-11 at 11 32 46 AM" src="https://user-images.githubusercontent.com/101395346/157850790-d08aa5be-36f4-457a-97f0-6a8c5b8ee5b3.png">


In conclusion, analyzing the text data and classifying into different classes is a critical task. This work is focused on applying common pre-preprocessing 
techniques and apply TF-IDF to vectorize the text and evaluate its effectiveness by running the data through several classifiers. The results showed that
Bernouillis Naive Bayes classifier is the better model for our data and study.
