## 20.2 $\Sigma$-sets

Note that the definition of $\text{split}$ accepts the function $Z$
that calculates the result _type_ of the function that calculates the result _object_.

Why do we pass the function as a whole?
A alternative one might consider is to pass the result $Z:\text{Set}$
and the function of the type $(x : X, y : \overline{Y(x)})\overline{Z}$,
thus delegating calculating the result type to the call site.
But the problem with this approach is that
the caller does not know what's contained inside the object of the $\Sigma$-type,
and the result type might depend on the specific object of $A$ or that of $B$.

It's also interesting to note that
the only way to eliminate an object of a $\Sigma$-type is via $\text{split}$,
so $Z$ will either call $\text{split}$ itself or (_eventually_) boil down to
something depending only on $X$ and $Y$ (since terms are finite).
