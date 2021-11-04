#chapter4 
Recalling that we can find a expected value $$E(u(x,y)) = \sum\sum u(x,y)f(x,y)$$ then letting $u(x,y) = (X-\mu_x )(Y-\mu_y )$ we get what is called the covariance of a $X$ and $Y$ denoted $Cov(x,y)$. Which we can then obtain the correlation coefficient $$\rho = \frac{Cov(X,Y)}{\sigma_x \sigma_y}$$

---

###### Example
Let $X$ and $Y$ have the joint pmf
$$f(x,y) = \frac{x+2y}{18}\quad x = 1,2\quad y=1,2$$
The [[Marginal Probability Mass Function]]'s are 
$$f_X (x) = \sum_{y=1}^{2}\frac{x+2y}{18} = \frac{x+3}{9}\quad x = 1,2$$
$$f_Y (y) = \sum_{x=1}^{2} \frac{x+2y}{18} = \frac{3+4y}{18}\quad y=1,2$$
The means of these marginals are
$$\mu_x = \sum_{x=1}^{2}x\frac{x+3}{9} = \frac{14}{9}$$
$$\mu_y = \sum_{y=1}^{2}y\frac{3+4y}{18} = \frac{29}{18}$$
Variances:
$$\sigma_{X}^{2} = \sum_{x=1}^{2}x^2 \frac{x+3}{9} = \frac{20}{81}$$
$$\sigma_{Y}^{2} = \sum_{y=1}^{2}y^2 \frac{3+4y}{18} = \frac{77}{324}$$
Now we have the necessary items to construct the covariance

$$Cov(X,Y) = \sum_{x=1}^{2}\sum_{y=1}^{2}xy\frac{x+2y}{18}-\mu_x\mu_y =$$ $$\sum_{x=1}^{2}\sum_{y=1}^{2}xy\frac{x+2y}{18} - \left( \frac{14}{9}\right) \left( \frac{29}{18}\right)= \frac{-1}{162}$$

and the correlation coefficient
$$\rho = \frac{-1/162}{\sqrt{(20/81)(77/324)}}=-0.025$$

---
##### Least Squares
Pictured here is what the correlation coefficient ($\rho$) tells us. We can see that a $\rho$ of 1 gives us a solid line with a positive slope. $\rho = -1$ gives us a solid line anything on the interval $(-1,1)^{*}$ results in some type of correlation. $\rho = 0$ means that there is no correlation in the data and as you can see no line can be determined by the data.
![[800px-Correlation_examples2.png]]
We can make a tread line to follow data with the tools that we demostrated in the above example. This tread line is called the least squares regression line and is defined as $$y = \mu_Y + \rho\frac{\sigma_Y}{\sigma_X}(x-\mu_x )$$