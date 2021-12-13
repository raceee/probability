#chapter6

The goal of a maximum likelihood estimator (MLE) is to find the optimal way to fit a distribution to the data. The distribution and parameter to be optimized is denoted as $$f(x;\theta )$$ in general. Where $\theta$ comes from a paramter space denoted as $\theta\in \Omega$. The computation goal for the MLE is to find a $\theta$ that maximizes the likelihood of the sample data. This found $\theta$ value for the maximal likelihood is denoted as $\hat{\theta}$.

---

To optimize the $\theta$ we need to create a function called the likelihood function

$$L = \prod_{i=1}^{n}f(x_i ;\theta)$$

How do we find the $\theta$?

---
###### Example 1
Let $$f(x ; \theta) = \theta x^{\theta - 1}\quad\quad 0<x<1\quad\quad \theta > 0$$

$$L = \prod_{i=1}^{n}\theta x_{i}^{\theta - 1} = \theta^{n}\left( \prod_{i=1}^{n}x_i \right)^{\theta - 1}$$

To make the optimization easier we will use the natural log since natural log is monotonically increasing. $$ln(L) =\ln\left( \theta^{n}\left( \prod_{i=1}^{n}x_i \right)^{\theta - 1} \right)$$ $$ = n\ln(\theta) + (\theta -1)\ln\left( \prod_{i=1}^{n}x_i\right)$$ $$L = n\ln(\theta) + (\theta -1)\sum_{i=1}^{n}\ln(x_i)$$

Ok we now have a function to find a crital points of $\theta$ we will do some classic calc 1.

$$\frac{d\ln(L)}{d\theta} = \frac{n}{\theta} + \sum_{i=1}^{n}\ln(x_i) = 0$$ Solving for $\theta$ we get $$\hat{\theta} = \frac{n}{-\sum\ln(x_i)}$$

That is for one variable. Now let's go to two variables.

---

###### Example 2

Let $x\sim N(\mu , \theta)$ Then $$f(x,\mu , \theta) = \frac{1}{\sqrt{2\pi}\theta}\exp (\frac{-1}{2\sigma^2}(x_i-\mu)^2)$$

$$L = \prod_{i=1}^{n}\frac{1}{\sqrt{2\pi}\theta}\exp (\frac{-1}{2\sigma^2}(x_i-\mu)^2)$$

$$L = \frac{1}{2\pi^{n/2}\theta}\exp (\frac{-1}{2\sigma^2}\sum(x_i-\mu)^2)$$

$$\ln(L) = \frac{n}{2}\ln(2\pi) - n\ln(\theta) -\frac{-1}{2\sigma^2}\sum(x_i -\mu)^2$$

From here we run into a problem. We  now have two variables ($\theta$, $\mu$) how do we optimize both of them? We take partial derivatives and then solve since we have two variables and two equations.


$$\frac{\partial\ln(L)}{\partial\mu} = \frac{1}{2\sigma^2}\sum-2(x_i - \mu) = 0$$

$$\frac{\partial\ln(L)}{\partial\sigma} = -\frac{n}{\sigma} + \frac{1}{\sigma^3}\sum(x_i - \mu)^2 = 0$$

The solutions ommitting the algebra $$\hat{\mu} = \frac{\sum x_i}{n} =\overline{x}$$ $$\hat{\sigma}^2 = \frac{\sum (x_i - \overline{x})^2}{n}$$

Substitute those back into $L$ and then you have the optimal parameters.

---

###### Definition 

If $E[u(X_1 , X_2 , \dots , X_n ) = \theta$, then the statistic $u(X_1 , X_2, \dots , X_n )$ is called an $\textbf{unbiased estimator}$ of $\theta$. Otherwise, it is said to be $\textbf{biased}$