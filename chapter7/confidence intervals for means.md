#chapter7
Here we will investigate how close the unbiased estimate (from the [[maximum likelihood estimator]]) for $\overline{X}$ comes to the unknown mean $\mu$. We do this by constructing a confidnece interval for the unknown paramter $\mu$. The construction is as follows

$$\left[\overline{X}-z_{\alpha /2}\left(\frac{\sigma}{\sqrt{n}}  \right), \overline{X} + z_{\alpha /2}\left(\frac{\sigma}{\sqrt{n}}  \right)\right]$$

---

In many applications, the sample sizes are small and we don not know the value of the standard deviation, althought some cases we might have a very good idea about its value. For this case we construct the confidence interval with the Student's t distribution from [[random functions associated with normal distributions]].

The construction is $$\left[\overline{x}-t_{\alpha /2}(n-1)\left(\frac{s}{\sqrt{n}}  \right), \overline{x} + t_{\alpha /2}(n-1)\left(\frac{s}{\sqrt{n}}  \right)\right]$$

---

Lastly there are one-sided confidence intervals for $\mu$. Which are constructed as $$(-\infty, \overline{x}+z_{\alpha}(\sigma/\sqrt{n}))$$
$$(\overline{x}-z_{\alpha}(\sigma/\sqrt{n}),\infty)$$

---

Confidence intervals for proportions exist as well. They are almost identical to the ones for means. A sample proportion is $\hat{p} = \frac{y}{n}$ Then the confidence interval is $$\left[\hat{p}\pm\sqrt{\frac{\hat{p}(1-\hat{p})}{n}} \right]$$

For two different populations with two different proportions:

$$\left[(\hat{p_1}-\hat{p_2})\pm\sqrt{\frac{\hat{p_1}(1-\hat{p_1})}{n_1}+\frac{\hat{p_2}(1-\hat{p_2})}{n_2}} \right]$$

