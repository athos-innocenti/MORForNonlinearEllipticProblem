# MORForNonlinearEllipticProblem

Given the objective of solving a parametric non-linear elliptic problem, this work compares three Model Order Reduction techniques: Proper Orthogonal Decomposition (POD), Physics Informed Neural Networks (PINNs), and POD-NN.
The methods are evaluated in terms of L2 and H1 errors, as well as computational Speed-Up.
The results indicate that PINNs exhibit the highest errors among the methods, while POD-NN achieves the best Speed-Up, solving the problem significantly faster than POD with an accuracy almost comparable to the latter.

The numerical solution of parametric PDEs plays a crucial role in various scientific and engineering applications. These problems often involve high-dimensional parameter spaces and
require multiple evaluations for different parameter values, leading to significant computational costs. Model Order Reduction techniques have emerged as a powerful approach to alleviate the computational burden associated with solving parametric PDEs. By reducing the dimensionality of the problem while preserving its essential features, MOR methods enable rapid and efficient approximations of the solution manifold. Among the most prominent MOR techniques are Proper Orthogonal Decomposition, data-driven methods such as Physics Informed Neural Networks, and hybrid approaches like POD-NN, which combines traditional projection-based methods with machine learning.
