## 20.2 $\Sigma$-sets

Note that the definition of $\text{split}$ accepts the function $Z$
that calculates the result _type_ of the function that calculates the result _object_.

Why do we pass the function as a whole?
A alternative one might consider is to pass the result $R:\text{Set}$
and the function of the type $(x : A, y : \overline{B(x)})\overline{R}$,
thus delegating calculating $R$ to the call site.
But the problem with this approach is that
the caller does not know what's contained inside the $\Sigma$ type,
and the result type might depend on the specific object of $A$ or that of $B$.
