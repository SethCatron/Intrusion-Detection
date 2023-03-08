# Intrusion-Detection
In this project, I started by loading the intrusion dataset from a CSV file into a Jupyter notebook. I created two scatter plots using matplotlib.pyplot, one for attribute 1 and attribute 2 (colored by "Intrusion"), and the other for attribute 2 and attribute 3 (colored by "Intrusion"). Then, I split the data into train and test sets using sklearn and trained a Support Vector Classifier with Poly, Linear, and RBF kernels. Next, I output confusion matrices and classification reports of the test set for each of the SV classifiers. I also trained a Random Forest Classifier on the dataset and output a confusion matrix and classification report of the test set with the Random Forest model. In both cases, I clearly labeled true positives, false positives, true negatives, and false negatives.
