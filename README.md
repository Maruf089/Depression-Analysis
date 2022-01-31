# Depression-Analysis
At First we made a google form for taking our own feelings in some file.
Google form Link  : https://forms.gle/PGo1ndnN8C5UJegq9

We apply different algorithms for analysis of our own depression and happiness Factor.
* ANN gives 76% accuracy in test set and 81% highest accuracy in validation set with 100 epoch. Used 4 dense layer with activation function relu and softmax in final layer for calssification.

* Diceion Tree Classifier gives 59% accuracy and weighted average f1-score.

![](DT.PNG)

* With min_support=0.1, min_confidence=0.6, min_lift=9, min_length=9 Appriori give 1406 rules.

* With K-Means Clusturing I got highest 30.32% score in prediction.

* In Linear Regression I calculate mean squarer error.

![](LinearRegression.PNG)

