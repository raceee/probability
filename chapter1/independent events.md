#chapter1 

For certain pairs of events, the occurrence of one of them may or may not change the probability of the occurrence of the other. In the latter case, they are said to be independent events.

Independent events effect [[conditional probability]]. Such that $P(B\vert A) = P(B)$ and $P(A\vert B) = P(A)$. Which is a good test.

###### Definition 1.4-1
Events $A$ and $B$ are independent if and only if $P(A\cap B) = P(A)P(B)$. Otherwise, $A$ and $B$ are called dependent events.

---

###### Theorem
If $A$ and $B$ are independent events, then the following pairs of events are also independent:
1. $A$ and $B'$
2. $A'$ and $B$
3. $A'$ and $B'$

---

###### Definition 1.4-2
Events $A$,$B$, and $C$ are mutually independent  if and only if the following two conditions hold:
1. $P(A\cap B) = P(A)P(B)$
2. $P(A\cap B\cap C) = P(A)P(B)P(C)$