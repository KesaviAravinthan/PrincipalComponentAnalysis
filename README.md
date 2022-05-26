# PrincipalComponentAnalysis
Concept of principal component analysis (PCA). Here PCA will be used to transform data into a lower dimensional space.


## Tasks

- Preprocess the data by subtracting the mean and dividing by the standard deviation of each attribute value. The resulting data should be zero-mean with variance 1.

- Compute the covariance matrix, where m is the sample size and x^(i) is the ith instance.

- Factorize the covariance matrix using singular value decomposition (SVD) and obtain the eigenvalues and eigenvectors. The SVD of a matrix Σ is a factorization of the form. Σ = USV. For symmetric, positive definite matrices U = V^T contains the eigenvectors and S is a diagonal matrix containing the respective eigenvalues.

- Project the data onto its first two principal components and plot the results.

- PCA implementation at Scikit-learn (sklearn.decomposition.PCA)
