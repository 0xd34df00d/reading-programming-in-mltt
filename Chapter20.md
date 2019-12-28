## 20.2 <img src="/tex/813cd865c037c89fcdc609b25c465a05.svg?invert_in_darkmode&sanitize=true" align=middle width=11.87217899999999pt height=22.465723500000017pt/>-sets

Note that the definition of <img src="/tex/88910dad7c67b8b58e2acf78ae6abc49.svg?invert_in_darkmode&sanitize=true" align=middle width=31.141646249999987pt height=22.831056599999986pt/> accepts the function <img src="/tex/5b51bd2e6f329245d425b8002d7cf942.svg?invert_in_darkmode&sanitize=true" align=middle width=12.397274999999992pt height=22.465723500000017pt/>
that calculates the result _type_ of the function that calculates the result _object_.

Why do we pass the function as a whole?
A alternative one might consider is to pass the result <img src="/tex/03842c884ea2b8bf83cdf579063ad522.svg?invert_in_darkmode&sanitize=true" align=middle width=49.138011449999986pt height=22.465723500000017pt/>
and the function of the type <img src="/tex/ff868a97c7fe55f39a1177d63f608c3e.svg?invert_in_darkmode&sanitize=true" align=middle width=125.94339944999997pt height=29.917526100000018pt/>,
thus delegating calculating <img src="/tex/1e438235ef9ec72fc51ac5025516017c.svg?invert_in_darkmode&sanitize=true" align=middle width=12.60847334999999pt height=22.465723500000017pt/> to the call site.
But the problem with this approach is that
the caller does not know what's contained inside the <img src="/tex/813cd865c037c89fcdc609b25c465a05.svg?invert_in_darkmode&sanitize=true" align=middle width=11.87217899999999pt height=22.465723500000017pt/> type,
and the result type might depend on the specific object of <img src="/tex/53d147e7f3fe6e47ee05b88b166bd3f6.svg?invert_in_darkmode&sanitize=true" align=middle width=12.32879834999999pt height=22.465723500000017pt/> or that of <img src="/tex/61e84f854bc6258d4108d08d4c4a0852.svg?invert_in_darkmode&sanitize=true" align=middle width=13.29340979999999pt height=22.465723500000017pt/>.