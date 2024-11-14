# Mathematics for Machine Learning: Linear Algebra

In this course on Linear Algebra we look at what linear algebra is and how it relates to vectors and matrices. Then we look through what vectors and matrices are and how to work with them, including the knotty problem of eigenvalues and eigenvectors, and how to use these to solve problems. Finally we look at how to use these to do fun things with datasets - like how to rotate images of faces and how to extract eigenvectors to look at how the Pagerank algorithm works.

Since we're aiming at data-driven applications, we'll be implementing some of these ideas in code, not just on pencil and paper. Towards the end of the course, you'll write code blocks and encounter Jupyter notebooks in Python, but don't worry, these will be quite short, focussed on the concepts, and will guide you through if you've not coded before.

At the end of this course you will have an intuitive understanding of vectors and matrices that will help you bridge the gap into linear algebra problems, and how to apply these concepts to machine learning.

## There are 4 programming assignments in this course

- [Identifying special matrices](1-IdentifyingSpecialMatrices.ipynb)

  When coding or solving data analysis problems, one problem that can occur is if your code encounters a special matrix that isn't invertible, or has an infinite number of eigenvectors, or similar. On other occasions, for example where you are reducing dimensionality, that might even be desirable! So here you will write a code fragment that traps for different types of special matrices before calling the python inversion routine, and classifies the type of special case encountered.

- [Gram-Schmidt process](2-GramSchmidtProcess.ipynb)

  The Gram-Schmidt process is a method for constructing an orthonormal basis of a space that a set of given vectors span. It can also be used to determine the dimension of that space, which may be different than the dimension of the vectors themselves or the number of vectors provided to span the space. In this assignment, you will complete a program that computes a Gram-Schmidt basis, and gives the dimension of a span of vectors.

- [Reflecting Bear](3-ReflectingBear.ipynb)

  In this assessment, you shall use the knowledge you have gained in changing basis to construct a matrix that performs a transformation that is easy in a particular basis, but complicated in our starting basis. Namely we shall help Panda Bear determine what his reflection will look like in a mirror that he has placed at an angle.

- [Page Rank](4-PageRank.ipynb)

  In this notebook, you'll build on your knowledge of eigenvectors and eigenvalues by exploring the PageRank algorithm. The notebook is in two parts, the first is a worksheet to get you up to speed with how the algorithm works - here we will look at a micro-internet with fewer than 10 websites and see what it does and what can go wrong. The second is an assessment which will test your application of eigentheory to this problem by writing code and calculating the page rank of a large network representing a sub-section of the internet.
