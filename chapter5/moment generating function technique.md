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
