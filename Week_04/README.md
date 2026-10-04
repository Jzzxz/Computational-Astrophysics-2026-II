# Week 04 — Root Finding and Simultaneous Equations

This week focuses on numerical methods for solving nonlinear equations and finding roots of functions.

The main objective is to approximate solutions of equations of the form

$$
f(x)=0,
$$

when an analytical solution is difficult or unavailable.

## Topics

- Root finding
- Bisection Method
- Newton-Raphson Method
- Secant Method
- Convergence and stopping criteria
- Approximate relative error
- Scarborough criterion
- Simultaneous equations

## Numerical Methods

### Bisection Method

A bracketing method that repeatedly divides an interval containing a root into two smaller intervals.

### Newton-Raphson Method

An iterative method that uses the derivative of the function to generate successive approximations to a root:

$$x_{n+1}=x_n-\frac{f(x_n)}{f'(x_n)}.$$

### Secant Method

An iterative method similar to Newton-Raphson, but it approximates the derivative using two previous points:

$$x_{n+1}=x_n-f(x_n)\frac{x_n-x_{n-1}}{f(x_n)-f(x_{n-1})}.$$

## Structure

- `Class_Exercises/` — Numerical methods and examples developed during class.
- `Homeworks/` — Homework problems and applications related to root finding and simultaneous equations.