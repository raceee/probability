#chapter2 
##### Mean
The mean of a random variable $X$ (or of its distribution) is $$\mu = \sum_{x\in S}xf(x)$$ As you can see this is the $x(E(X)) = \sum_{x\in S} xf(x)$.

---

##### Variance
The variance of a random variable is defined as $$\sigma^2 = \sum_{x\in S}(x-\mu)^2 f(x)$$ Notice the $x-\mu$ term this is a value that represents the point's distance from the mean. Thus it follows that this equation is one that represents the variance.

---

##### Standard Deviation
Standard deviation is just the square root of the variance.

---

##### Moment
###### Definition 2.3-1
Let $X$ be a random variable of the discrete type with pmf (found in [[discrete random variables]]) and space $S$. if $$E(e^{tX}) = \sum_{x\in S}e^{tx}f(x)$$ exists and is finite for $-h < t < h$, then the function defined by $$M(t) = E(e^{tX})$$ is called the $\textbf{moment-generating function of X}$. This function is often abbreviated as mgf.