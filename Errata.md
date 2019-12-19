*Errata* (sort of)

* P. 92, judgements (14.15-17):
looks like it should be <img src="/tex/bd28b29032812b6c2f34bbf2bbee12ad.svg?invert_in_darkmode&sanitize=true" align=middle width=144.78926054999997pt height=24.7161288pt/>
instead of <img src="/tex/8dca0ab1a3311a299651db0ec21443fe.svg?invert_in_darkmode&sanitize=true" align=middle width=109.17273179999998pt height=24.7161288pt/> in the contexts
(otherwise it doesn't make sense from the types point of view).

* P. 101, middle of the page: looks like we need <img src="/tex/436e026ed24a8323d34a7cefa2c64a9d.svg?invert_in_darkmode&sanitize=true" align=middle width=43.835549999999984pt height=22.648391699999998pt/> as the set of constructors, not <img src="/tex/ad92ad37f0d196e080c1ecb48b2f6e9a.svg?invert_in_darkmode&sanitize=true" align=middle width=43.835549999999984pt height=22.648391699999998pt/>.

* P. 106, second line from above: the value of the expression shall be <img src="/tex/3a0a5838a63ec9213f7f936637e0ecbb.svg?invert_in_darkmode&sanitize=true" align=middle width=186.53553599999998pt height=24.65753399999998pt/>.
  We shall pass the same function to the recursive call, otherwise this evaluation rule does not make sense (and does not even type check).
