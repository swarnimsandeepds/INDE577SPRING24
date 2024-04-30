K-Nearest Neighbors (kNN)


The K-NN algorithm assumes a resemblance between the new case/data and the existing cases and assigns the new case to the category that is most similar to the extant categories.
The K-NN algorithm maintains all available data and classifies new data points based on their similarity. This means that when fresh data comes, it may be quickly sorted into a suitable category using the K-NN method.
K-NN algorithms can be used for both regression and classification, however they are more commonly utilized for classification problems.
K-NN is a nonparametric algorithm, which means it makes no assumptions about the underlying data.
It is also called a lazy learner algorithm because it does not learn from the training set immediately instead it stores the dataset and at the time of classification, it performs an action on the dataset.
KNN algorithm at the training phase just stores the dataset and when it gets new data, then it classifies that data into a category that is much similar to the new data.

## Visual Overview of KNN
<img src="/Supervised%20Machine%20Learning/images/KNN.gif" width="600">


Comprehensive Guide to KNN

The K-Nearest Neighbors (KNN) algorithm operates in the following way:

    Number of Neighbors (K): Decide on the number of nearest neighbors to consider.
    Distance Measurement: Calculate the distance between the query point and all other points in the dataset.
    Sorting Distances: Order these distances and select the top K nearest neighbors from this sorted list.
    Determine Output: For classification, the label that appears most frequently among these neighbors is assigned to the query point.

Principal Attributes of KNN

    Non-parametric: It makes no assumptions about the underlying data distribution.
    Adaptable: Effective for both classification and regression tasks.

Steps to Implement KNN

    Data Preparation: Scale your data and divide it into training and testing segments.
    Select K: Choose a suitable number for K.
    Compute Distances: Use a method such as Euclidean distance to measure the distance between points.
    Algorithm Training: Apply the KNN algorithm to the training data.
    Prediction: Use the model to predict outcomes for the test data.

Performance Metrics for KNN

    Accuracy: The percentage of accurately predicted outcomes.
    Confusion Matrix: Particularly valuable in multi-class classification scenarios.
    Mean Squared Error (MSE): In regression, it quantifies the average squared differences between predicted and actual values.

Beginning with KNN

    Requirements: A grasp of Python and fundamental machine learning principles.
    Tools: Implement the algorithm using libraries like Scikit-learn to simplify the process.
    Testing Variables: Experiment with various K values and distance calculations to optimize performance.
