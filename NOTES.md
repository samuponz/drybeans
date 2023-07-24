# NOTES

Regarding attributes:
 - ShapeFactor3 is Compactness squared (SF3 = CO^2)
 - Solidity and ShapeFactor4 are really similar. This is likely to happen because S = A/C while SF4 = A/EE and C $\approx$ EE, which is the Equivalent Ellipse (L/2*l/2*$\pi$).

 
## ASSETS:
 - https://archive.ics.uci.edu/dataset/602/dry+bean+dataset
 - https://www.kaggle.com/datasets/sansuthi/dry-bean-dataset



# PRE-PROCESSING:
- Missing values
- Outliers (Boxplot?)
- Undersampling or Oversampling
- Class balancing
- Class aggregation
- PCA

## FEATURE SCALING
By scaling the data, we can ensure that each feature has an equal impact on the model’s performance, and the model can make more accurate predictions.
In addition to improving the performance of machine learning models, feature scaling can also help to speed up the convergence of optimization algorithms such as gradient descent. By scaling the data to a common range, the optimization algorithm can converge more quickly and efficiently.


Feature scaling is not important for algorithms such as random forest or decision trees which are scaling invariant.


## FEATURE SELECTION
It’s almost rare that all the variables in the dataset are useful for building a model. Adding redundant variables reduces the model’s generalization capability and may also reduce the overall accuracy of a classifier. Furthermore, adding more variables to a model increases the overall complexity of the model.



# IDEE:
- “k-fold” campionamento di instanze in modo da avere classi equilibrate. Campionamento → diversi training con diversi dati → robustezza
- creare missing values in dataset completi


# TODO:
 - analisi dati
 - analisi relazioni tra le feature
 - analisi distribuzione istanze nelle classi

## Scaletta
# DATASET
- Introduzione
# OUTLIERS REMOVAL
- SVM
# FEATURE SELECTION
- Correlation
- K-Best
- Random Forest
# FEATURE EXTRACTION
- PCA
# CLASSIFICATION
- Random Forest
- SVM
- Neural Network
# SCORE
- Accuracy, precision, ...
- Kappa
- +++

