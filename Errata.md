## Errata (sort of)

* P. 92, judgements (14.15-17):
looks like it should be <img src="/tex/bd28b29032812b6c2f34bbf2bbee12ad.svg?invert_in_darkmode&sanitize=true" align=middle width=144.78926054999997pt height=24.7161288pt/>
instead of <img src="/tex/8dca0ab1a3311a299651db0ec21443fe.svg?invert_in_darkmode&sanitize=true" align=middle width=109.17273179999998pt height=24.7161288pt/> in the contexts
(otherwise it doesn't make sense from the types point of view).

* P. 101, middle of the page: looks like we need <img src="/tex/436e026ed24a8323d34a7cefa2c64a9d.svg?invert_in_darkmode&sanitize=true" align=middle width=43.835549999999984pt height=22.648391699999998pt/> as the set of constructors, not <img src="/tex/ad92ad37f0d196e080c1ecb48b2f6e9a.svg?invert_in_darkmode&sanitize=true" align=middle width=43.835549999999984pt height=22.648391699999998pt/>.

* P. 106, second line from above: the value of the expression shall be <img src="/tex/3a0a5838a63ec9213f7f936637e0ecbb.svg?invert_in_darkmode&sanitize=true" align=middle width=186.53553599999998pt height=24.65753399999998pt/>.
  We shall pass the same function to the recursive call, otherwise this evaluation rule does not make sense (and does not even type check).

* P. 120, mid: it should be "<img src="/tex/512dea171bdc78854239cde5c41ff79e.svg?invert_in_darkmode&sanitize=true" align=middle width=70.16367599999998pt height=24.7161288pt/> is equal to <img src="/tex/68a52e0d582d47ec96072cc7a777a2b8.svg?invert_in_darkmode&sanitize=true" align=middle width=70.98558555pt height=24.7161288pt/>" (with the extra <img src="/tex/3e18a4a28fdee1744e5e3f79d13b9ff6.svg?invert_in_darkmode&sanitize=true" align=middle width=7.11380504999999pt height=14.15524440000002pt/> parameter), since <img src="/tex/478c6659a4f7054bb1c40c48c6579299.svg?invert_in_darkmode&sanitize=true" align=middle width=19.90872179999999pt height=24.7161288pt/> is ternary.

* P. 124, bottom, <img src="/tex/ecea226b5977d1a327732124dccb8969.svg?invert_in_darkmode&sanitize=true" align=middle width=9.132448049999992pt height=22.831056599999986pt/>-formation: the premise should read <img src="/tex/b38b30128fd89712a2e8afaea1fb2e47.svg?invert_in_darkmode&sanitize=true" align=middle width=37.99094804999999pt height=22.465723500000017pt/>, not <img src="/tex/7d8f1e2fe0fe3d4ba814f26f96dc0892.svg?invert_in_darkmode&sanitize=true" align=middle width=50.73073169999999pt height=22.465723500000017pt/>.

* P. 128, top definition: it should be <img src="/tex/9c87eaa2879d41a6ad4084c5095ff772.svg?invert_in_darkmode&sanitize=true" align=middle width=33.02523179999999pt height=24.65753399999998pt/> instead of <img src="/tex/58c3d799e58ecf11b5f22cdb0077c1b8.svg?invert_in_darkmode&sanitize=true" align=middle width=40.60513379999999pt height=27.123336899999988pt/>.

* P. 129, last line of the judgement: it should be <img src="/tex/0b81ebf9fb4fae1dfcf9b8b2ee7d4d28.svg?invert_in_darkmode&sanitize=true" align=middle width=77.59537004999999pt height=24.65753399999998pt/> instead of <img src="/tex/d4592284de89899ff40475422596aa15.svg?invert_in_darkmode&sanitize=true" align=middle width=77.58008444999999pt height=24.65753399999998pt/>
  since <img src="/tex/332cc365a4987aacce0ead01b8bdcc0b.svg?invert_in_darkmode&sanitize=true" align=middle width=9.39498779999999pt height=14.15524440000002pt/> is not even in scope.

* P. 130, <img src="/tex/df33724455416439909c33a7db76b2bc.svg?invert_in_darkmode&sanitize=true" align=middle width=12.785434199999989pt height=19.1781018pt/>-subset-equality: the equalities in the conclusion live in <img src="/tex/0083044378857e88010b87ac252fa5d0.svg?invert_in_darkmode&sanitize=true" align=middle width=45.71340014999999pt height=22.465723500000017pt/>,
  that is, they should be <img src="/tex/5a7d8d90e70ded488dfa46241b0f028f.svg?invert_in_darkmode&sanitize=true" align=middle width=104.51589059999999pt height=24.65753399999998pt/> and <img src="/tex/0ada80d83ba896749a443ad15bfd8b7a.svg?invert_in_darkmode&sanitize=true" align=middle width=106.41471885pt height=24.65753399999998pt/> respectively.

* P. 143, second Application rule: the conclusion should read <img src="/tex/6ca5c720aa30c652348c33905328dbe7.svg?invert_in_darkmode&sanitize=true" align=middle width=92.20897619999998pt height=24.65753399999998pt/>,
  since <img src="/tex/8e830a5ab471143f1bb80e525c09bbaa.svg?invert_in_darkmode&sanitize=true" align=middle width=15.24170009999999pt height=14.15524440000002pt/> and <img src="/tex/2ca230a36892a5d996272ca45a782d16.svg?invert_in_darkmode&sanitize=true" align=middle width=15.24170009999999pt height=14.15524440000002pt/> aren't even in scope.
