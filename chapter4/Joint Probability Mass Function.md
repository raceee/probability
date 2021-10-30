#chapter4
Let $X$ and $Y$ be two random variables defined on a discrete space. Let $S$ denote the correspoinding two-dimensional space of $X$ and $Y$, the two random variables of the discrete type. 

The probability that $X = x$ and $Y = y$ is denoted by $$f(x,y) = P(X=x, Y=y)$$ This funciton is called the $\textbf{joint probability function}$.

Properties of the of the joint pmf are:
1. $0\leq f(x,y) \leq 1$
2. $\sum_{x,y\in S}\sum f(x,y) = 1$
3. $P[(X,Y)\in A] = \sum_{x,y\in S}\sum f(x,y)$, where A is a subset of the space S.

Example:
Let the joint pmf of X and Y be $$f(x,y) = \frac{xy^2}{30}, \quad x = 1,2,3, \quad y = 1,2$$
The [[Marginal Probability Mass Function]]'s of the random variables are $$f_x = \sum_{y=1}^2 \frac{xy^2}{30} = \frac{x}{6}$$

$$f_y = \sum_{x=1}^3 \frac{xy^2}{30} = \frac{y^2}{5}$$

Are these random variables [[independent or dependent]]?

$$f_x f_y = \frac{x}{6}\frac{y^2}{5} = \frac{xy^2}{30}$$ So they are independent.