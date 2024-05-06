How to perform dimensionality reduction ?
PCA.
The idea of PCA is simple — reduce the number of variables of a data set, while preserving as much information as possible.

Principal components are new variables that are constructed as linear combinations or mixtures of the initial variables. These combinations are done in such a way that the new variables (i.e., principal components) are uncorrelated and most of the information within the initial variables is squeezed or compressed into the first components.

HOW DO YOU DO A PRINCIPAL COMPONENT ANALYSIS?

step 1 : Standardize the range of continuous initial variables

step 2 : Compute the covariance matrix to identify correlations

step 3 : Compute the eigenvectors and eigenvalues of the covariance matrix to identify the principal components

step 4 : Create a feature vector to decide which principal components to keep ( sorting the eigen values in descending order )

step 5 : Recast the data along the principal components axes
