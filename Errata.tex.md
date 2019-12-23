## Errata (sort of)

* P. 92, judgements (14.15-17):
looks like it should be $z(v) \in \text{Set}(C(s'(v)))$
instead of $z(v) \in C(s'(v))$ in the contexts
(otherwise it doesn't make sense from the types point of view).

* P. 101, middle of the page: looks like we need $\mathbb{N} + \mathbb{N}$ as the set of constructors, not $\mathbb{N} \times \mathbb{N}$.

* P. 106, second line from above: the value of the expression shall be $e(a, b, c, (x)\text{treerec}(c(x), e)$.
  We shall pass the same function to the recursive call, otherwise this evaluation rule does not make sense (and does not even type check).

* P. 120, mid: it should be "$A(a, b, c)''$ is equal to $A''(a, b, c)$" (with the extra $c$ parameter), since $A''$ is ternary.

* P. 124, bottom, $\forall$-formation: the premise should read $A\ \text{set}$, not $A\ \text{prop}$.

* P. 128, top definition: it should be $(z)\text{T}$ instead of $(z)\text{T}''$.

* P. 130, $+$-subset-equality: the equalities in the conclusion live in $A + B$,
  that is, they should be $z =_{A+B} inl(x)$ and $z =_{A+B} inr(y)$ respectively.
