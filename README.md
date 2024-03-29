# PHYS 451: Numerical Methods 
## Spring 2021
Dr. Daugherity, Abilene Christian University

This repository is for code and data files.  All other course information is posted on Canvas.

### Important Note 
Github's notebook renderer is trash.  Pages will often not display correctly. 
**One workaround is to view the pages on [nbviewer](https://nbviewer.jupyter.org/github/mdaugherity/Numerical-2021/tree/main/)**.  
Another approach is to open the files directly from Colab.

# OUTLINE
## Introduction and Review
* [Class 1-13-21](intro/PHYS_451_Class_1_13_21.ipynb) - Python and Google Colab Cheat Sheet 
* [Class 1-20-21](intro/PHYS_451_Class_1_20_21.ipynb) - Numerical Errors, IEEE 754 Floating Point numbers
* [Homework Report Template](Report_Template.ipynb) - Use this for all homework
* [LaTeX Crash Course](intro/LaTeX_Crash_Course.ipynb) - How to make nice equations
## Systems of Linear Equations
* [Class 1-22-21](systems/PHYS_451_Class_1_22_21.ipynb) - Examples solving linear systems
## Interpolation and Fitting
* [Interpolation](fit/Week_3_Interpolation.ipynb) - scipy.interpolate.interp1d 
* [Polynomial Fits](fit/Week_3_Fitting_Polynomials.ipynb) - np.polyfit and polyval
* [Linear Algebra Least Squares](fit/Week_3_Linear_Algebra_Fits.ipynb) - matrix methods for least squares
* [Exponential Fits](fit/Week_3_Exponential_Fit.ipynb) - transforming data
## Root Finding
* [Class 2-5-21](roots/Class_2_5_2021.ipynb) - first experiments with root finding
* [Bisection Demo](roots/Week_4_Bisection_Demo.ipynb) - simple bisection algorithm 
* [Newton and Secant](roots/Week_4_Newton.ipynb) - simple demos of Newton and Secant methods
* [Using root_solve](roots/Week_4_root_solve.ipynb) - how to use root_solve
* [Practice Problems](roots/CH4_Root_Finding_Examples.ipynb) - [Solutions](roots/CH4_Root_Finding_Solutions.ipynb)
## Derivatives
* [First Derivatives](diffs/Week_5_Derivative_Types.ipynb) - examples of forward, backward, and centered differences
* [Derivative Examples](diffs/Week_5_Derivatives.ipynb) - how to find derivatives for functions and data points
## Integrals
* [Newton-Cotes Demo](integrals/Week_6_Newton_Cotes_Integrals.ipynb) - simple implementation of rectangle, trapezoid, and Simpson's method
* [Numerical Integral Errors](integrals/Week_6_Integral_Errors.ipynb) - compare errors in trapezoid, Simpson, and Romberg integration 
## ODE IVP
* [Euler's Method](ode/Week_7_Euler.ipynb) - simple method for IVP
* [How to use solve_ivp](ode/Week_7_solveivp.ipynb) - examples using scipy.integrate.solve_ivp
* [Coupled Systems and Stiff Problems](ode/Class_3_22_2021.ipynb) - examples from class on 3-21-2021
## ODE BVP
* [Shooting Method](ode/Week_8_BVP.ipynb) - doing the shooting method with root_scalar and solve_ivp
* [How to use solve_bvp](ode/Week_8_solvebvp_demo.ipynb) - examples using scipy.integrate.solve_bvp
## Random ("Stochastic") Methods
* [Chaos](random/Week_9_Chaos.ipynb) - special topic on chaos with logistic maps 
* [MC Integration](random/Week_10_MC_Integration.ipynb) - Monte Carlo Integration


