#chapter3
Normal distributions are observed when we look at large populations.
$$f(x) = \frac{1}{\sigma\sqrt{2\pi}}\exp \left[ -\frac{(x-\mu)^2}{2\sigma^2}\right],\quad\quad -\infty < x < \infty$$

However, this [[pdf]] is very complex we can preform what is called a $\textbf{standard normal distribution}$. We do this as follows $$\phi(z) = P\left( \frac{X-\mu}{\sigma} \leq \frac{x-\mu}{\sigma} \right) = P\left( Z \leq z \right)$$

This transformation is motivated by the following theorems

###### Theorem 3.3-1
If $X$ is $N(\mu , \sigma^2 )$, $Z = (X-\mu)/\sigma$ is $N(0,1)$

---

###### Theorem 3.3-2
If the random variable $X$ is $N(\mu,\sigma^2),\quad\sigma^2 > 0$ then the random variable $V = (X-\mu)^2 /\sigma^2 = Z^2$ is $\mathbb{X}^2 (1)$ or the [[chi-square distribution]] with 1 degree of freedom.

---