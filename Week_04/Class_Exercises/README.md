# Week 04 — Class Exercises

This directory contains the class exercises developed during Week 04.

The exercises focus on numerical root-finding techniques and their implementation in Python.

## Topics

- Bisection Method
- Newton-Raphson Method
- Secant Method
- Approximate relative error
- Scarborough stopping criterion
- Convergence of iterative methods
- Applications of root-finding methods

## Methods

### Bisection Method

The Bisection Method starts from an interval $[x_l,x_u]$ containing a root and repeatedly reduces the interval by evaluating the midpoint

$$
x_r=\frac{x_l+x_u}{2}.
$$

### Newton-Raphson Method

The Newton-Raphson Method generates successive approximations using

$$
x_{n+1}
=
x_n-\frac{f(x_n)}{f'(x_n)}.
$$

### Secant Method

The Secant Method avoids the explicit calculation of the derivative by using two previous approximations:

$$
x_{n+1}
=
x_n-
f(x_n)
\frac{x_n-x_{n-1}}
{f(x_n)-f(x_{n-1})}.
$$

The implementations emphasize understanding the numerical algorithms rather than relying on built-in root-finding routines.