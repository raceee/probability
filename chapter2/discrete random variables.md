#chapter2

##### Definition 2.1-1
Given a random experiment with an outcome space $S$, a function $X$ that assigns one and only one real number $X(s) = x$ to each element $s$ in $S$ is called a random variable. The space of $X$ is set of real numbers $\{ x: X(s) = x, s\in S\}$, where $s\in S$ mean that the elements $s$ belongs to the set $S$.

---

##### Definition 2.1-2
The pmf $f(x)$ of a discrete random variable $X$ is a function that satisfies the following properties:
1. $f(x) > 0, \quad x\in S$
2. $\sum_{x\in S} f(x) = 1$
3. $P(X\in A) = \sum_{x}f(x)\quad A\subset S$

---

Consider a collection of $N = N_1 + N_2$ similar objects, $N_1$ of them belonging to one of two dichotomous classes (red chips, say) and $N_2$ of them belonging to the second class (blue chips, say). Here we define the $\textbf{hypergeometric distribtution}$

$$f(x) = P(X=x) = \frac{{N_1 \choose x}{N_2\choose n-x}}{{N\choose n}}$$