This README file contains the description of the final project in the course Interpretable methods of classification and knowledge discovery.

In general, we are solving the task of binary classification. It means that there are only two possible values for the target class (usually denoted as + and -).

As an input we are given a train set in which the class labels for the object is known, and a test dataset in which the objects and their features are given but without the class label.

We will follow the lazy learning approach in the classification task, which means that the step for building the classification is eliminated, and as soon as we get test object (query object) we need to assign a class label to it, using existing data from the train set.
