#chapter5 
##### Example 5.1-1
Let X have a gamma distribution with [[pdf]] $$f(x) = \frac{1}{\Gamma(\alpha )\theta^{\alpha}} x^{\alpha - 1}e^{\frac{-x}{\theta}}, \quad 0 < x < \infty$$
where $\alpha > 0$, $\theta > 0$. Let $Y = e^{X}$, so that the support of $Y$ is $1 < y < \infty$. For each $y$ in the support, the [[cdf]] of Y is $$G(y) = P(Y\leq y) = P(e^{X}\leq y) = P(X\leq ln(y))$$ where $$G(y) = \int_{0}^{ln(y)}\frac{1}{\Gamma (\alpha)\theta^{\alpha}} x^{\alpha -1}e^{-x/\theta}dx$$ and thus the [[pdf]] $g(y) = G'(y)$ of Y is $$g(y) = \frac{1}{\Gamma (\alpha)\theta^{\alpha}}(\ln y)^{\alpha - 1}e^{-\ln(y)/\theta}\left( \frac{1}{y}\right) = \frac{1}{\Gamma (\alpha)\theta^{\alpha}}\frac{(\ln y)^{\alpha -1 }}{y^{1+1/\theta}}$$ This is called the loggamma pdf. The mean and variance are as follows.
$$\mu = \frac{1}{(1-\theta)^\alpha}$$
$$\sigma^2 = \frac{1}{(1-2\theta)^\alpha}-\frac{1}{(1-\theta)^{2\alpha}}$$
 
 --- 
 The next example in the book is long and tedious but it introduces the Cauchy pdf:
 $$g(x) = \frac{1}{\pi (1+x^2)}$$