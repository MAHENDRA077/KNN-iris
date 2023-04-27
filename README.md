# KNN-Iris

### Dataset : https://archive.ics.uci.edu/ml/machine-learning-databases/iris/iris.data

## KNN:(K-nearest neighbors)
    1. Supervised Learning.
    2. used with both Regression and classification.
    3. predictions are based on distance b/w data points.
    
## Metrics:
        1. Euclidean Metrix ----> used with Quantative data
        2. Hamming Disatnce  -----> used with Categorical Data
        3. Minkowski Distance -----> generalized version of Euclidean and used with real-valued
        
## Finding Optimal K - Value:
         1. error plot 
         2. accuracy plot
         3. K=sqrt(total_no_of_samples)/2   [https://stackoverflow.com/questions/11568897/value-of-k-in-k-nearest-neighbor-algorithm]
 
 ### Code-Reference:  https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html
