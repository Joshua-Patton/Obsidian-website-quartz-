This essentially gives us a the existence of a unique solutions to our interpolation of several finite points.

# Lagrangian interpolating polynomial
Although who wants to solve systems of equations, Lagrange came up with something better,
Namely if we consider the Polynomials called the nth base Lagrange Polynomials
$$
L_n(x_j)=
\begin{cases}
1, & j=n,\\
0, & j\neq n.
\end{cases}
$$
If we times this by $y_{n}$ we get a function that is 0 for other n, and $y_n$ for the value of $x_{n}$
Thereby we consider the Lagrange interpolating Polynomials as $$
P(x)=\sum_{i=1}^{N} y_i L_i(x)
$$
Which gives us our desired interpolating polynomial.

Lastly how do we find $L_n$, well we want a function which is zero for ever $x_i$ except $x_n$, so something like
$$
L_n(x)=\prod_{\substack{1\le j\le N\\ j\neq n}}
\frac{x-x_j}{x_n-x_j}
$$
The bottom equals the top when $x=x_{n}$, and zero for all other values of $x_{j}$,


