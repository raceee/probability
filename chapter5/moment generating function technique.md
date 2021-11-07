#chapter5 
Additionally to the other sections of techniques for determining the distribution of a function of random variables with known distributions (namely: [[change of variables technique]], [[distribution function technique]], [[several random varibles]]).

---

#### Theorem 
If $X_1 , X_2 , \dots , X_n$ are independent random variables with respective mooment generating functions $M_{X_i}(t)$, $i = 1,2,3,\dots ,n$ where $-h_i < t < h_i, i = 1,2,3,4,\dots n$, for positive numbers $h_i$, $i = 1,2,\dots , n$ then the moment-generating function of $Y = \sum_{i=1}^{n}a_i X_i$ is $$M_{Y}(t) = \prod_{i=1}^{n}M_{X_{i}}(a_i t),\quad where\quad -h_i < a_i t < h_i \quad i=1,2,\dots ,n$$


##### Corollary

If $X_1 , X_2 , \dots X_n$ are observations of a random sample from a distribution with moment-generating function $M(t)$, where $-h < t < h$, then
* the moment-generating function of $Y = \sum_{i=1}^{n}X_i$ is $$M_{Y}(t) = \prod_{i=1}^{n} M(t) = [M(t)]^n,\quad -h < t < h$$
* the moment-generating function of $\bar{X} = \sum_{i=1}^{n}(1/n)X_i$ is $$M_{\bar{X}}(t) = \prod_{i=1}^n M\left(\frac{t}{n}\right) = \left[ M\left(\frac{t}{n}\right)\right]^n$$
---

###### Examples

Let $X_1, X_2, X_3$ denote the outcomes of $n$ Bernoulli trials, each with probability of success $p$. The mgf of $X_i$, $i=1,2,\dots ,n$ is $$M(t) = q + pe^t,\quad -\infty < t < \infty$$
if $$Y = \sum_{i=1}^{n}X_i$$then$$M_Y (t) = \prod_{i=1}^{n}(q + pe^t ) = (q + pe^t )^n$$ Thus Y is $b(n,p)$

---

Let $X_1 , X_2 , X_3$ be the observations of a random sample of size $n=3$ from the exponential distribution having mean $\theta$ and, of course, mgf $M(t) = 1/(1-\theta t), t<1/\theta$ The mgf of $Y = X_1 + X_2 + X_3$ is $$M_Y (t) = \left[ (1-\theta t)^{-1}\right]^3 = (1 -\theta t)^{-3}, \quad\quad t < 1/\theta$$  We can see that after applying $$M_Y (t) = \prod_{i=1}^{n}\left[\frac{1}{(1-\theta t )^{1}}\right]$$ we get$$\left[\frac{1}{(1-\theta t )^{1}}\right]^3$$ which is the gamma distribution with alpha value of $\alpha = 3$. Thus $Y$ has a gamma distribution.

---

#### More Theorems

Let $X_1, X_2, \dots , X_n$ be independent chi-square random variables with $r_1 , r_2,\dots, r_n$ degrees of freedom respectively. Then $Y = X_1 + X_2 + \dots + X_n$ is $\mathbb{X}^2 (r_1 + r_2 + \dots + r_n)$


Let $Z_1, Z_2, \dots, Z_n$ have standard normal distributions, $N(0,1)$. If these random variables are independent, then $W = Z_{1}^{2}+Z_{2}^{2}+\dots+Z_{n}^{2}$ has a distribution that is $\mathbb{X}^2(n)$

If $X_1, X_2, \dots, X_n$ are independent and ahve normal distributions $N(\mu_i , \sigma_{i}^{2}), i=1,2,\dots,n$ respectively, then the distribution of $$W = \sum_{i=1}^{n}\frac{(X_i - \mu_i)^2}{\sigma_{i}^{2}}$$ is $\mathbb{X}^2(n)$