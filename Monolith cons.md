---
tag: architecture, monolith
URL: https://hackernoon.com/why-we-abandoned-monoliths-overview-of-modular-architecture-part-i-zt1u3457
title: Why we abandoned monoliths
---
Architecture pattern
- mvc: elixir enforce MVC (server architecture)
	- controller tiep nhan request
	- dua vao model de manipulate/ update data
	- tra result ve view


The difference between
- MVC
them layer + them tuong tac 
- MVP
- MVVM
- Viper

Cons
- dependency: work can't be divided for teammates
- navigation: k the implement independently
- testing coverage: unable to functional separate test
- team knowledge gap

More reading src:
- [Types of Monoliths](https://triare.net/insights/common-architecture-for-mobile-application/?ref=hackernoon.com)