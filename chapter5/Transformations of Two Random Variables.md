#chapter5
Remember from [[Transformation of a Single Random Variable]] in the continuous case, if $Y = u(X)$ was an increasing or decreasing function of X, with inverse $X = v(Y)$, then the [[pdf]] of Y was $$g(y) = \vert v'(y)\vert f[v(y)], \quad c < y < d$$ For two random variables this single valued function changes to $$g(y_1 , y_2 ) = \vert J\vert f[v_1 (y_1 , y_2 ), v_2 (y_1 , y_2 )]$$
In this case we find the support $S_y$ of $Y_1$, $Y_2$ by considering the mapping of the supprt $S_x$ of $X_1$, $X_2$ under the transformation $y_1 = u_1 (x_1 , x_2)$ $y_2 = u_2 (x_1 , x_2 )$. This method is called the [[change of variables technique]]

---
Example 1:
Let $X_1$ and $X_2$ be independent random variables, each with [[pdf]]
$$f(x) = e^{-x}, \quad 0 < x < \infty$$

Hence, their [[Joint Probability Mass Function]] is $$f(x_1 )f(x_2 ) = e^{-x_1 -x_2}, \quad 0 < x_1 < \infty, \quad 0 < x_2 < \infty$$

Let us consider $$Y_1 = X_1 - X_2, \quad Y_2 = X_1 + X_2$$
Thus, 
$$x_1 = \frac{y_1 + y_2}{2},\quad x_2 = \frac{y_2 + y_1}{2}$$
with the [[Jacobian]] being:

$$J = \frac{1}{2}$$

---
Example 2:

Consider $$f(x,y) = 2(x+y), \quad 0 < x < y < 1$$ Find the [[pdf]] of $T = xy$ and $s = x$

---