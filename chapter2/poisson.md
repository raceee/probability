#chapter2 

Some experiments result in counting the number of times particular events occur at given times or with given physical objects

---

##### Definition 2.6-1
Let the number of occurrences of some event in a given continuous interval be counted. Then we have an approximate Poisson process with parameter $\lambda>0$ if the following conditions are satisfied:
1. Then numbers of occurences in nonoverlapping subintervals are independent
2. The probability of exactly one occurrence in a sufficiently short subinterval of length $h$ is approximately $\lambda h$.
3. The probability of two or more occurrences in a sufficinetly short subinterval is essentially zero.

---

The distribution of probabilty associated with this process has a special name. We say that the random variable X has a $\textbf{Poisson distribution}$ if its pmf is of the form $$f(x) = \frac{\lambda^x e^{-x}}{x!}$$