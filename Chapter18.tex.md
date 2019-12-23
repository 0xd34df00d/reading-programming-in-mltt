## Witness-preservation

Note that subset-introduction rule (p. 126 mid)
doesn't (syntactically) keep the witness of $P(a) true$ in $a \in \{ x \in A | P(x) \}$.
Consequently, the witness term is not available in Subset-elimination,
so I'm not sure how $c$ or $C$ in the corresponding rules are supposed to use it.
Does this make type-checking undecidable (since term finding is undecidable)?
Or is it just some sloppy wording/formulation in the part of the theory that presumably gets less attention?
