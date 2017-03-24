# python_basics
Aim
Implementation of the Fixed-Point Iteration Algorithm in Python.
Background
In numerical analysis, fixed-point iteration is a method of computing fixed points
of iterated functions.
More specifically, given a function f defined on the real numbers with real values
and given a point x in the domain of f , the fixed point iteration is
0
x n+1 = f ( x n ), n = 0, 1, 2, 3....
which gives rise to the sequence x
point x .
0 ,
x 1 , x 2
... which is hoped to converge to a
If f is continuous, then one can prove that the obtained x is a fixed point of f ,
i.e.,
f (x) = xMore generally, the function f can be defined on any metric space with values in
that same space.
The Algorithm
1. Given a function of type x = f (x)
2. Now make an assumption for the value of x, labelling it a.
3. Compute the value of:
f (a),
4. Compute the value of:
f (f (a)),
5. Compare the values obtained in step 3 and step 4
1. Case 1: If the difference between these two is less than the permissible
error, print the root and exit.
2. Case 2: Otherwise set a = f(a) and continue.
6. Return to step 3.
Assignment
1. Implement the Fixed-Point Iteration method in Python
2. Calculate the solution for:
i.
1
x = 1 +1/x
ii.
x=(x^3+2)/7
Note: Use Initial Guess = 1, and Allowed Error = 0.0005, for both.Reference
