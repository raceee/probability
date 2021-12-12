#chapter1

#### Definition
Probabilty is a real-valued set function $P$ that assigns, to each event $A$ in the sample sapce $S$, a number $P(A)$, called th eprobability of the event $A$, such that the following properties are satisfied:
1. $P(A)\geq 0$
2. $P(S)=1$
3. If $A_1 , A_2 , A_3 , \dots$ are events and $A_i \cap A_j = \emptyset$ $i\neq j$, then $$P(A_1 \cup A_2 \cup \dots \cup A_k) = P(A_1) + P(A_2) + \dots + P(A_k)$$ for each positive integer $k$, and $$P(A_1 \cup A_2 \cup \dots ) = P(A_1) + P(A_2) + \dots $$ for an infinite, but countable, number of events.

---

##### Theorems
$$P(A) = 1 - P(A')$$
$$P(A\cup B) = P(A) + P(B) - P(A\cap B)$$
$$P(A\cup B\cup C) = P(A) + P(B) + P(C) - P(A\cap B) - P(A\cap C) - P(B\cap C) + P(A\cap B\cap C)$$