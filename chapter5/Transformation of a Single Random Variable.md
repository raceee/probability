#chapter5
Let X be a random variable of the continuous type. If we consider a function of X -- say, $Y = u(X)$ then Y must also be a random variable that has its own distribution. If we can find its [[cdf]], say, $$G(y) = P(Y\leq y) = P[u(X) \leq y]$$ then its [[pdf]] is given by $g(y) = G'(y)$. 

We now illustrate the [[distribution function technique]] 

---

By making a simple observation, we can sometimes shortcut the [[distribution function technique]] by using what is frequently called the [[change of variables technique]]. Let $X$ be a continuous-type random variable with pdf $f(x)$ with support $c_1 < x < c_2$. We begin this discussion by taking $Y = u(X)$ as a continuous increasing function of $X$ with inverse function $X = v(Y)$. Say the support of $X$, namely $c_1 < x < c_2$, maps onto $d_1 = u(c_1 ) < y < d_2 = u(c_2 )$, the support of $Y$. Then the cdf of Y is
$$G(y) = P(Y\leq y) = P[u(X)\leq y] = P[X\leq v(y)], \quad d_1 < y < d_2$$ and $$G'(y) = g(y) = f[v(y)][v'(y)]$$
