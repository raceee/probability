#chapter5 
Usually a sample is taken from a normally distributed function $N(\mu ,\sigma^2)$. We are interested in estimating the parameters $\mu$ and $\sigma^2$ or in testing conjectures about these paramters.


---
##### Theorem 


If $X_1 , X_2 ,\dots , X_n$ are $n$ mutually independent normal variables with means $\mu_1 , \mu_2 , \dots , \mu_n$ and variances $\sigma_{1}^{2} , \sigma_{2}^{2}, \dots , \sigma_{n}^{2}$, respectively, then the linear function $$Y = \sum_{i=1}^{n}c_i X_i$$ has the normal distribution $$N\left( \sum_{i=1}^{n}c_i \mu_i , \sum_{i=1}^{n}c_{i}^{2}\sigma_{i}^{2} \right)$$.


###### Corollary
If $X_1 , X_2 ,\dots , X_n$ are observation of a random sample of size $n$ from the normal distribution $N(\mu ,\sigma^2 )$, then the distribution of the sample mean $\overline{X} = 1/n\sum_{i=1}^n X_i$ is $N(\mu , \sigma^2 /n)$

---

##### Theorem 5.5-2
Let $X_1 , X_2 , \dots , X_n$ be observations of a random sample of size $n$ from the normal distribution $N(\mu, \sigma^2 )$. Then the sample mean is $$\overline{X} = \frac{1}{n}\sum_{i=1}^n X_i$$
The sample variance is $$S^2 = \frac{1}{n-1}\sum_{i=1}^{n}(X_i -\overline{X})^2$$ are independent and $$\frac{(n-1)S^2}{\sigma^2} = \frac{\sum_{i=1}^{n}(X_i -\overline{X})^2}{\sigma^2}\quad is \quad\mathbb{X}^2 (n-1)$$

---

##### Theorem 5.5-3
(Student's t distribution)
Let $$T = \frac{Z}{\sqrt{U/r}}$$