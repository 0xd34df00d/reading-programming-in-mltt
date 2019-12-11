The text mentions (p. 26) $\lambda x. x$ as an example of a canonical expression,
yet canonical expressions are defined to be closed and _saturated_.

It might seem that $\lambda x. x$ is _not_ saturated,
but the notation in the book uses a different notation for the syntactic notion of the function,
and in this particular case the actual unsaturated function would have been written as $(x)x$.

$\lambda$ is best viewed as a primitive canonical constant (or like a `newtype`-introduced constructor in Haskell),
and, in fact, the book explicitly defines it this way around pp. 48-49.
