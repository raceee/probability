##### Inclass Portion

4.1 , 4.2, 5.1, 5.3, 5.4

---

###### 4.1
* given $f(x,y)$ find $P(x > y+2 )$
* Find $E(x) = E[h(x,y)] = \sum_x \sum_y u(x,y)f(x,y)$
*  Binomial Distributions $$f(x) = {n\choose n_1}p_1^{x_1}(1 - p_1)^{n-x_2}$$
*  Multinomial Distributions $$f(x_1 , x_2 ) = \frac{n!}{x_1 !x_2 !(n-x_1 -x_2)!} p_1^{x_1}p_2^{x_2}(1 - p_1 - p_2 )^{n-x_1 - x_2}$$
###### Examples
* Given $f(x,y)$ find $P(X > Y + 2 )$
* Find $f_x (x)$ in this case you would sum over $\sum_y f(x,y)$
* Find $E(x)$ in this case you would $$E(x) = x\sum_{x}\sum_{y} f(x,y)$$
* Find $E(h(x,y))$ similar to the previous question but $x$ term becomes $h(x,y)$ thus$$E(h(x,y)) = \sum_ x\sum_y h(x,y)f(x,y)$$
* Multinomial Distribution: an extension of the binomial distribution. Where the binomial distribution has two classes success or failure, the multinomial distribtuion has $n+1$ classes. $n$ classes for successes of different types and then and extra class for the *failure* class. For example, lets say you have two different discrete variables $x_1$ and $x_2$. They have different sucess conditions but they can also both fail, hence there are three categories. 
	* Note: let's say that we have the multinomial distribution $f(x_1 , x_2)$ and we want to find $f(x_1 )$. Since we are only focused on $x_1$'s state of success or failure then we just have a binomial distribution.
---

###### 4.2
* Find $Cov(x,y) = E(xy) - E(x) E(y)$
* Correlation Coefficient $$\rho = \frac{Cov(x,y)}{\sigma_x \sigma_y}$$Where $$\sigma_x^{2} = E(x^2) - E(x)$$

---

###### 5.1
[[Transformation of a Single Random Variable]]
The goal of this section is to solve questions like: "Given $f(x)$ find the distribution of $Y = u(x)$". There are two main techniques for doing this.
* cdf to cdf
$$G(y) = P(Y \leq y) = P[u(x) \leq y]$$
* If $Y = u(x)$ is one-to-one on the interval then you can use $$g(y) = f(v(y))\vert v'(y)\vert$$ to find the distribution of $Y$. Professor said to show your support in a graph to indicate that you know that the function $u(x)$ is one-to-one.

---

###### 5.3
[[Transformations of Two Random Variables]]

###### Examples
* Find $P(x_1 + x_2 = 2)$. 
Since these variables are independent then you can break up this expression. So instead of finding $P(x_1 + x_2 = 2)$ we can compute $$P(x_1 = 0)P(x_2 = 2)\quad\quad P(x_1 = 2)P(x_2 = 0)\quad\quad P(x_1 = 1)P(x_2 = 1)$$
* Find $E[x_1 (x_2 - 1)^2]$ Similary to the above, independence gives us convient properties. We can write $$E[x_1 (x_2 - 1)^2] = E(x_1 )E((x_2 - 1)^2)$$ Notice that $E((x_2 - 1)^2)$ is just the variacne of this question. This is the example, but the context for this question was that it was a binomial distribution so $\mu = np = 1$. Thus $E((x_2 - 1)^2)$ being the variance means that $\sigma^2 = np(1-p) = 0.8$ Thus $$E[x_1 (x_2 - 1)^2] = E(x_1 )E((x_2 - 1)^2) = (1)0.8 = 0.8$$
---

###### 5.4
* recognize moment generating functions of all distributions?
* $M_y (t) = M_x (t)^{n}$


---

##### Take Home

4.4 , 5.2

###### 4.4
* finding regression line

---

###### 5.2
* Really long problems

---