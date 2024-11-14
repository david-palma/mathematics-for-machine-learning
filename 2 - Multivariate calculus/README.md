# Mathematics for Machine Learning: Multivariate Calculus

This course offers a brief introduction to the multivariate calculus required to build many common machine learning techniques. We start at the very beginning with a refresher on the “rise over run” formulation of a slope, before converting this to the formal definition of the gradient of a function. We then start to build up a set of tools for making calculus easier and faster. Next, we learn how to calculate vectors that point up hill on multidimensional surfaces and even put this into action using an interactive game. We take a look at how we can use calculus to build approximations to functions, as well as helping us to quantify how accurate we should expect those approximations to be. We also spend some time talking about where calculus comes up in the training of neural networks, before finally showing you how it is applied in linear regression models. This course is intended to offer an intuitive understanding of calculus, as well as the language necessary to look concepts up yourselves when you get stuck. Hopefully, without going into too much detail, you'll still come away with the confidence to dive into some more focused machine learning courses in future.

## There are 2 programming assignments in this course

- [Backpropagation](1-Backpropagation.ipynb)

  In this assignment, you will train a neural network to draw a curve by implementing backpropagation by the chain rule to calculate Jacobians of the cost function. The neural network will then be trained using a (pre-implemented) stochastic steepest descent method, and will draw a series of curves to show the progress of the training. You will have to copy and edit pre-written python code in this assessment, but will not need to write new code. It should be tractable even to learners with little coding experience, so long as you don't panic about the code and work through each line diligently.

- [Fitting the distribution of heights data](2-FittingDistribution.ipynb)

  In this worksheet you will implement the steepest descent algorithm on the least squares fitting problem for modelling the distribution of heights in a population with a Gaussian.
