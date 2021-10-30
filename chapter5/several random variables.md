#chapter5 
What if there are lots of variables
---
### Example 5.3-3
An electronic device runs until one of its three components fails. The lifetimes (in weeks), $X_1$, $X_2$, $X_3$, of these components are independent, adn each has the Weibull pdf
$$f(x) = \frac{2x}{25}e^{(-x/5)^2}$$

The probability that the device stops running in the first three weeks is equal to 
$$1 - P(X_1 >3, X_2 > 3, X_3 > 3) = 1 - P(X_1 > 3)P(X_2 > 3)P(X_3 > 3) $$
$$ = 1-\left( \int_{3}^{\infty} f(x) dx\right)^3$$
$$ = 1-\left(\left[-e^{-(x/5)} dx\right]_{3}^{\infty}\right)^3$$
$$= 0.66$$

---

## Theorem
Say $X_1$,$X_2$,$\dots$,$X_n$ are independent random varibles and $Y = u_1 (X_1 )u_2 (X_2 )\dots u_n (X_n)$. If $E[u_i (X_i )], i = 1,2,\dots, n$, exist, then 
$$E(Y) = E[u_1 (X_1)u_2 (X_2)\dots u_n (X_n)] = E[u_1 (X_1 )]\dots E[u_n (X_n)]$$