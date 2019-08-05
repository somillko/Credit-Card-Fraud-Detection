# Credit-Card-Fraud-Detection
Credit Card fraud detection using creditcard.csv dataset hosted on Kaggle

# Performing the task using two different types of anomaly detection methods
I have used the following techniques:
•	Isolation Forest Algorithm
•	Local Outlier factor Algorithm
# Local Outlier Factor (LOF)
The anomaly score of each sample is called Local Outlier Factor. It measures the local deviation of density of a given sample with respect to its neighbours. It is local in that the anomaly score depends on how isolated the object is with respect to the surrounding neighbourhood.
# Isolation Forest Algorithm
The Isolation Forest ‘isolates’ observations by randomly selecting a feature and then randomly selecting a split value between the maximum and minimum values of the selected feature.
Recursive partitioning creates a decision tree that strives to correctly classify members of the population by splitting it into sub-populations based on several dichotomous independent variables
Since recursive partitioning can be represented by a tree structure, the number of splitting required to isolate a sample is equivalent to the path length from the root node to the terminating node.
This path length, averaged over a forest of such random trees, is a measure of normality and our decision function.
Random partitioning produces noticeably shorter paths for anomalies. Hence, when a forest of random trees collectively produce shorter path lengths for particular samples, they are highly likely to be anomalies.

The full run able code is the jupyter notebook file.
For more details Refer to the report.
