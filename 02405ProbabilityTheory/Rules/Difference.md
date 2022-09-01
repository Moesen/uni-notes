### Difference rule
If occurence of A implies occurence of B, then $P(A) \leq P(B)$, and the difference between these probabilities is the probability that B occurs and A does not:
$$
P(B \text{ and not } A) = P(BA^{c}) = P(B) - P(A)
$$
**Proof**
In other words, the assumption is that every outcome in A is an outcome in B, so A is a subset of B. Since B can be partioned into A and (B but not A), by the addition rule. 
$$
\begin{align}
 P(B) &= P(A) + P(BA^{c}) \\
 \rightarrow P(B) &=P(A)+P(B) - P(A) = P(B)
\end{align}
$$
