# Mathematics for Machine Learning: PCA

This intermediate-level course introduces the mathematical foundations to derive Principal Component Analysis (PCA), a fundamental dimensionality reduction technique. We'll cover some basic statistics of data sets, such as mean values and variances, we'll compute distances and angles between vectors using inner products and derive orthogonal projections of data onto lower-dimensional subspaces. Using all these tools, we'll then derive PCA as a method that minimizes the average squared reconstruction error between data points and their reconstruction.
At the end of this course, you'll be familiar with important mathematical concepts and you can implement PCA all by yourself. If you're struggling, you'll find a set of jupyter notebooks that will allow you to explore properties of the techniques and walk you through what you need to do to get on track. If you are already an expert, this course may refresh some of your knowledge.

## There are 2 programming assignments in this course

- [Numpy Tutorial](1-NumpyTutorial.ipynb)

  This notebooks teaches you the basics of numpy, the scientific computing library for Python.

- [Mean/Covariance of a data set and effect of a linear transformation](2-MeanCovariance.ipynb)

  We will now look at computing means and (co)variances of data sets and the effect of linear transformations of the data sets on the mean and covariance. For this, we will write some code snippets.

- [Inner products and angles](3-DistancesAnglesBetweenImages.ipynb)

  Compute distances/angles between images.

- [Orthogonal projections](4-OrthogonalProjections.ipynb)

  Here, you will implement orthogonal projection which projects data onto lower-dimensional subspaces. You will then apply this to the problem of "eigenfaces" which will help you understand the application of orthogonal projection in the real world.

- [Principal Components Analysis (PCA)](5-PCA.ipynb)

  We will implement the PCA algorithm. We will first implement PCA, then apply it (once again) to the MNIST digit dataset.
