#chapter5
Let X be a random variable of the continuous type. If we consider a function of X -- say, $Y = u(X)$ then Y must also be a random variable that has its own distribution. If we can find its [[cdf]], say, $$G(y) = P(Y\leq y) = P[u(X) \leq y]$$ then its [[pdf]] is given by $g(y) = G'(y)$. 

The following change of variable technique is called the [[cdf]] technique:
Example 5.1-1
Let X have a gamma distribution with [[pdf]] $$f(x) = \frac{1}{\Gamma(\alpha )\theta^{\alpha}} x^{\alpha - 1}e^{\frac{-x}{\theta}}, \quad 0 < x < \infty$$
where $\alpha > 0$, $\theta > 0$. Let $Y = e^{X}$, so that the support of $Y$ is $1 < y < \infty$. For each $y$ in the support, the [[cdf]] of Y is $$G(y) = P(Y\leq y) = P(e^{X}\leq y) = P(X\leq ln(y))$$ where $$G(y) = \int_{0}^{ln(y)}\frac{1}{\Gamma (\alpha)\theta^{\alpha}}$$