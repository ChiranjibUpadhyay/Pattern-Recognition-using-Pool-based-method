# Pattern-Recognition-using-Pool-based-method
##Objective
Doing pattern recognition on various datasets using a pool based method( Part of active learning technique) using PySpark

##Method and advantage
traditional techniques of classification mostly involes training the model with the entire training dataset consuming more CPU time, instead in active learning what we do is devide the training dataset into two catagories--
###1.labelled training set and
###2.unlabeled pool set
we train with less no of datapoints using labeled train set and if the accuracy is less than certain amount(say 90%), we take some datapoints from unlabeled pool set and add them to the labeled training set and train the model with it.
If the accuracy we get is more than the required we no longer need to train the model again,Thus improving the model training time and efficiency.
