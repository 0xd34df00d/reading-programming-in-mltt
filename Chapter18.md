## Witness-preservation

Note that subset-introduction rule (p. 126 mid)
doesn't (syntactically) keep the witness of <img src="/tex/797d6142124445d0c389e5d9844e52f8.svg?invert_in_darkmode&sanitize=true" align=middle width=65.18482244999998pt height=24.65753399999998pt/> in <img src="/tex/96bc5da96f8a62efa478b5512f491f27.svg?invert_in_darkmode&sanitize=true" align=middle width=126.61705154999999pt height=24.65753399999998pt/>.
Consequently, the witness term is not available in Subset-elimination,
so I'm not sure how <img src="/tex/3e18a4a28fdee1744e5e3f79d13b9ff6.svg?invert_in_darkmode&sanitize=true" align=middle width=7.11380504999999pt height=14.15524440000002pt/> or <img src="/tex/9b325b9e31e85137d1de765f43c0f8bc.svg?invert_in_darkmode&sanitize=true" align=middle width=12.92464304999999pt height=22.465723500000017pt/> in the corresponding rules are supposed to use it.
Does this make type-checking undecidable (since term finding is undecidable)?
Or is it just some sloppy wording/formulation in the part of the theory that presumably gets less attention?
