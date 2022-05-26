# Direct-and-Iterative-Solver-of-Linear-Systems-Master
Project from my numerical analysis II in college, where we discuss, outline and compare algorithms for numerically solving linear systems of equations.

From the write up:

In this paper, we will be evaluating numerical methods for direct and iterative solvers of linear systems. From class we have discussed the various methods; Gauss elimination with pivoting techniques, Jacobi Iterative Method, Gauss-Seidel Iterative Method, Successive Over-Relaxation Method, Iterative Refinement Method, and Conjugate Gradient Method. In this paper, using Python programming language, we will discuss how each method evaluates various linear systems of equations, and then we will discuss the complexity, accuracy, and stability of each method.
• Complexity will be judged based on the standard of Big O notation. Meaning we will discuss the methods makeup and then show the Big O notation of that individual method and compare each method. Showing quantitively evidence of the complexity as well.
• Accuracy is judged based on error calculated from each method. An accurate approximation is judged desirable when being below a tolerance value of 10−15. This standard of accuracy is chosen because we feel that in academia, and in application that error less than this tolerance provides a relatively accurate approximation.
• Stability, in our project, is judged upon convergence. Meaning a method is declared stable if the norm converges to zero or the residuals converge to zero. This important because this converges shows that method is becoming more and more accurate over time. Divergence of the norm or residuals declares that a method is unstable.
