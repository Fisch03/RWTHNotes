---
aliases: [Konvergenz, Divergenz, konvergent, divergent]
tags:
- AfI
---
## Definition
Eine Folge $(a_{n})\subset\mathbb{R}$ besitzt den Grenzwert $a\in\mathbb{R}$ oder $\mathbb{C}$, falls
$$\forall\varepsilon>0,\exists n_{0}\in\mathbb{N}\cdot|a_{n}-a|\leq\varepsilon\forall n\geq n_{0}$$
Wir schreiben $\displaystyle\lim_{n\rightarrow\infty}a_{n}=a$ oder $a_{n}\xrightarrow{n\rightarrow\infty} a$ und nennen $(a_{n})$ *konvergent* andernfalls *divergent*

Die Konvergenz lässt sich auch mit [[Cauchy-Folge|Cauchy-Folgen]] nachweisen

## Bestimmt/Unbestimmt divergent
[[Schranken|Unbeschränkte]] Folgen die gegen $\pm\infty$ "konvergieren" heissen *bestimmt divergent*
$a_{n}=(-1)^{n}$ ist *unbestimmt divergent*


## Beispiele
1. $(2^{n})_{n\leq0}$ kein Grenzwert, divergent, $(\textbf{i}^{n})_{n\geq1}$ divergent, $((-1)^n)_{n\in\mathbb{N}}$ divergent
2. $a_{n}:=\frac{1}{n}$ ist konvergent mit Grenzwert $a=0$ d.h. $\displaystyle\lim_{n\rightarrow\infty}\frac{1}{n}=0$
   