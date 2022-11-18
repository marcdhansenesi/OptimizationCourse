![](SU_Seal_-_red-transparent.gif) Mathematical Optimization
============================================================

_Mathematical Optimization_ is a high school course in 5 units, comprised of a total of 56 lessons. The first three units are non-Calculus, requiring only a knowledge of Algebra; the last two units require completion of Calculus AB. All of the units make use of the Julia programming language to teach students how to apply basic coding techniques to solve complex and relevant mathematical problems.

The curriculum has complementary [IJulia notebooks](https://github.com/sisl/OptimizationCourse) for all lessons involving programming (and some that do not).

These lessons in Mathematical Optimization were written in 2014 by Julia Roberts, a math teacher at Cupertino High School in the Fremont Union High School District, in conjunction with Dr. Mykel Kochenderfer, professor of Aeronautics and Astronautics at Stanford University, through a grant from the National Science Foundation. They were edited, updated, and turned into Julia notebooks in 2015 by Renee Trochet, a math teacher at Eastside College Preparatory in East Palo Alto, also in conjunction with Dr. Kochenderfer and funded by the NSF.

The goals of these lessons are:

* to increase exposure of high school students to current topics of interest in mathematics, including optimization and the use of programming as a tool
* to increase the number and variety of students interested in STEM fields 
* to provide students with better preparation for future studies in STEM fields.

[Introduction and Acknowledgements](introduction-and-acknowledgements.pdf)

Unit 1: Introductory Topics
---------------------------

This unit introduces the foundational concepts of optimization, iteration, and recursion, as well as laying groundwork with introductory topics like vectors, secant method, Fibonacci numbers, and three-point intervals. It introduces students to the Julia language including downloading and navigating, basic operations, if/else, loops, and basic string and array language. Unit 1 finishes with students writing a program using the secant method to find the root of a function.

[Unit overview](unit1-overview.pdf)  
[Download PowerPoint (entire unit)](MO-unit1-introduction.zip)  
[Download Problem Set Masters (entire course)](MO-problemsets.zip)  
Individual Lessons (pdf):  
[1.1 Optimization](MO-unit1-pdfs/1.1optimization.pdf): overview, about the course  
[1.2 Vectors](MO-unit1-pdfs/1.2vectors.pdf): definition and applications  
[1.3 Iteration and Recursion 1](MO-unit1-pdfs/1.3iterationandrecursion.pdf): definition and examples including Fibonacci numbers  
[1.4 Iteration and Recursion 2](MO-unit1-pdfs/1.4iterationandrecursion2.pdf): secant method  
[1.5 Iteration and Recursion 3](MO-unit1-pdfs/1.5iterationandrecursion3.pdf): finding a three-point interval containing a max/min  
[1.6 Julia Basics](MO-unit1-pdfs/1.6juliabasics.pdf): access, basic operations  
[1.7 If-Else](MO-unit1-pdfs/1.7if-else.pdf): structure in Julia, test conditions  
[1.8 Iterative Loops](MO-unit1-pdfs/1.8iterativeloops.pdf): for and while loops in Julia  
[1.9 Arrays](MO-unit1-pdfs/1.9arrays.pdf): definition, commands and operations  
[1.10 Secant Method](MO-unit1-pdfs/1.10secantmethod.pdf): students write a program to find roots using secant method

Unit 2: Unbounded Optimization Without Calculus
-----------------------------------------------

This unit teaches students to use the Julia language in optimization. Students write programs to find a three-point interval containing an optimum, to find a minimum and maximum within that interval, and to find global optima using interval searches as well as the Sawtooth method. Then students extend these concepts into two or more variables using brute force, Hooke-Jeeves, and cyclic coordinate methods.  Unit 2 finishes with brief overviews of stochastic methods, including Monte Carlo, simulated annealing, and genetic algorithms.

[Unit overview](unit2-overview.pdf)  
[Download PowerPoints (entire unit)](MO-unit2-unbounded.zip)  
Individual Lessons (pdf):  
[2.1 Introduction](MO-unit2-pdfs/2.1intro.pdf): definitions, local and global  
[2.2 Three-Point Interval](MO-unit2-pdfs/2.2threepointinterval.pdf): students write a program to find a 3-point inerval  
[2.3 Minimum 1 Brute Force](MO-unit2-pdfs/2.3minimum1brute.pdf): students write a program to minimize in 3D using brute force  
[2.4 Minimum 2 Intervals](MO-unit2-pdfs/2.4minimum2golden.pdf): students write a program to minimize in 3D using Golden Section intervals  
[2.5 Minimum 3 Slopes](MO-unit2-pdfs/2.5minimum3slopes.pdf): students write a program to minimize in 3D using slopes  
[2.6 Maximum and Minimum](MO-unit2-pdfs/2.6maxandmin.pdf): students convert programs to maximizing and learn about "maximizing a negative"  
[2.7 Global 1 Testing Points](MO-unit2-pdfs/2.7global1testpoints.pdf): find global minimum by testing points on an interval  
[2.8 Global 2 Sawtooth](MO-unit2-pdfs/2.8global2sawtooth.pdf): Slope of curved functions, Sawtooth Method for global maximum  
[2.9 Introduction to 3D](MO-unit2-pdfs/2.9intro3D.pdf): functions in 2 variables, 3D graphing  
[2.10 Minimizing in 3D 1 Brute Force](MO-unit2-pdfs/2.10minimum3D1brute.pdf): basic minimization techniques in 2 variables  
[2.11 Hooke-Jeeves](MO-unit2-pdfs/2.11minimum3D2hooke-jeeves.pdf): Hooke-Jeeves Pattern Seach method  
[2.12 Cyclic Coordinates](MO-unit2-pdfs/2.12minimum3D3cycliccoord.pdf): Cross sections, Cyclic Coordinate Search method  
[2.13 Extensions](MO-unit2-pdfs/2.13extensions.pdf): Maximizing, adjustments for 3+ variables  
[2.14 Stochastic 1](MO-unit2-pdfs/2.14stochastic1def,monte.pdf): definition, convergence, Monte Carlo  
[2.15 Stochastic 2](MO-unit2-pdfs/2.15stochastic2annealing,genetic.pdf): simulated annealing, genetic algorithms  

Unit 3: Linear Programming
--------------------------

This unit introduces the idea of optimization within linear constraints. It begins by introducing the graphical premise of linear programming, basic matrix operations, and row reduction by pivoting. Then, it leads students through setting up and solving a standard maximum problem from words to solution, starting with converting words to constraints, setting up a simplex tableau, then maximizing through pivoting with the help of programs they write in the Julia language. Unit 3 finishes with duality/minimization and non-standard constraints.

[Unit overview](unit3-overview.pdf)  
[Download PowerPoints entire unit](MO-unit3-linprog.zip)  
Individual Lessons (pdf):  
[3.1 Introduction and Graphical](MO-unit3-pdfs/3.1introandgraphical.pdf): constraints, feasible region, corner points by graphing  
[3.2 Matrix Operations](MO-unit3-pdfs/3.2matrixoperations.pdf): operations, inverses, division  
[3.3 Row Reduction Solving](MO-unit3-pdfs/3.3rowreduxsolving.pdf): array commands in Julia, row replacement, Gaussian elimination  
[3.4 Building a Simplex Tableau](MO-unit3-pdfs/3.4buildingsimplex.pdf): converting equations, setting up  
[3.5 Pivoting](MO-unit3-pdfs/3.5pivoting.pdf): reading a solution, pivoting  
[3.6 Simplex Maximization](MO-unit3-pdfs/3.6simplexmax.pdf): choosing a pivot, solving  
[3.7 Full Problems](MO-unit3-pdfs/3.7fullproblems.pdf): students solve two problems from words to completion  
[3.8 Duality and Minimization](MO-unit3-pdfs/3.8dualityandmin.pdf): setting up dual matrices, solving minimization problems  
[3.9 Nonstandard Maximization](MO-unit3-pdfs/3.9nonstandardmax.pdf): setting up nonstandard constraints, solving  

Unit 4: Unbounded Optimization With Calculus
--------------------------------------------

This unit begins with students writing simple programs to find derivatives, integrals and roots using familiar Calculus concepts. After learning how to download packages through GitHub (in this case, Calculus.jl), students refine their work with the Sawtooth method in unit 2, then apply curve sketching concepts to find maxima and minima of smooth, 1-variable functions. Following a crash course in multivariable differentiation including gradients, Hessians, and eigenvalues, students write two programs to minimize functions in 2 variables, then briefly extend these concepts to maximization and functions in more than 2 variables.

[Unit overview](unit4-overview.pdf)  
[Download PowerPoints entire unit](MO-unit4-calculus.zip)  
Individual Lessons (pdf):  
[4.1 Numerical Derivatives](MO-unit4-pdfs/4.1nderivs.pdf): students write a program to find a numerical derivative  
[4.2 Simpson integrals](MO-unit4-pdfs/4.2simpsonintegrals.pdf): Simpson's Rule, integral approximation  
[4.3 Newton's Method](MO-unit4-pdfs/4.3newton.pdf): Newton's Method to find roots  
[4.4 Packages and Sawtooth](MO-unit4-pdfs/4.4packages,sawtooth.pdf): downloading packages, refining Sawtooth slopes  
[4.5 Curve Sketching](MO-unit4-pdfs/4.5curvesketching.pdf): first and second derivatives in curve sketching  
[4.6 Concavity Verification](MO-unit4-pdfs/4.6concavityverification.pdf): verifying max/min using concavity  
[4.7 Gradients](MO-unit4-pdfs/4.7gradients.pdf): meaning of gradients, finding gradients  
[4.8 Applications of Gradients](MO-unit4-pdfs/4.8applicationsofgradients.pdf): evaluating gradients and graphical applications  
[4.9 Finding Hessians](MO-unit4-pdfs/4.9findingHessians.pdf): finding a Hessian, symmetry  
[4.10 Applications of Hessians](MO-unit4-pdfs/4.10applicationsofhessians.pdf): determinants and eigenvalues, concavity implications  
[4.11 Gradients 1: Steepest Descent](MO-unit4-pdfs/4.11gradient1steepest.pdf): using Calculus package for steepest descent minimization  
[4.12 Gradients 2: Conjugate Gradient](MO-unit4-pdfs/4.12gradient2conj-grad.pdf): conjugate gradient method for minimization  
[4.13 Extensions](MO-unit4-pdfs/4.13extensions.pdf): maximizing, globals, beyond 3D  

Unit 5: Constrained Optimization With Calculus)
-----------------------------------------------

This unit walks students through the steps of using steepest-descent methods within a feasible region bounded by constraints. After combining multiple subroutines together to solve problems from start to finish, students learn about penalty functions and finish with an overview of Pareto optimality and Markov Decision Processes.

[Unit overview](unit5-overview.pdf)  
[Download PowerPoint entire unit](MO-unit5-calcconst.zip)  
Individual Lessons (pdf):  
[5.1 Introduction](MO-unit5-pdfs/5.1intro.pdf): background, setup and graphing feasible regions in 2 varianbles  
[5.2 Foundations](MO-unit5-pdfs/5.2foundations.pdf): finding descent and feasible cones in 2 variables  
[5.3 Phase 1](MO-unit5-pdfs/5.3phase1.pdf): minimizing within constraints using steepest descent  
[5.4 Phase 2](MO-unit5-pdfs/5.4phase2.pdf): vector normalization and boundary movement  
[5.5 Big Problems](MO-unit5-pdfs/5.5bigproblems.pdf): solving constrained minimization problems from equations to solution  
[5.6 Penalty Functions](MO-unit5-pdfs/5.6penaltyfunctions.pdf): setup and optimization with quadratic loss functions  
[5.7 Interior Penalty Functions](MO-unit5-pdfs/5.7interiorpenalty.pdf): setup and optimization with barrier functions  
[5.8 Pareto](MO-unit5-pdfs/5.8Pareto.pdf): design and criterion space, Pareto front, Pareto improvements  
[5.9 MDPs](MO-unit5-pdfs/5.9MDPs.pdf): Markov property, MDPs, POMDPs  
