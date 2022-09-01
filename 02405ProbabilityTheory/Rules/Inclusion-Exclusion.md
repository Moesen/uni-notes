### Inclusion-Exclusion
$$
P(A \cup B) = P(A) + P(B) - P(AB)
$$
*Remarks:* Here $A \cup B$ means A or B or both (union) while AB means both A and B (intersection $A\cap B$). This is the modification of the addition rule for events A and B that overlap, as the diagram on page 22.

![[inclusionexclusion.png]]

**Proof**
As the diagram shows, the sets $AB^{c}$, $AB$, and $A^cB$ form a partition of $A \cup B$, so
$$
P(A \cup B ) = P(AB^{c}) + P(AB) + P(A^{c}B)
$$
Similarly
$$
\begin{align}
	P(A) &= P(AB^{c}) + P(AB)\\
	P(B) &= P(A^{c}B) + P(AB)
\end{align}
$$
so
$$
P(A) + P(B) = P(AB^{c}) + 2P(AB) + P(A^{c} B)
$$
This is the same expression as for $P(A \cup B)$, but P(AB) is included twice. SUbtracting P(AB) excludes one of these terms to give the inclusion-exclusion formula.
