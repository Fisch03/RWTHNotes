---
aliases: []
tags:
- AfI
---
## Definition
Auf einer Menge $K$ seien zwei Verknüpfungen definiert:
$$+: \mathbb{K}\times\mathbb{K}\text{ (genannt "Addition")}$$
$$\cdot: \mathbb{K}\times\mathbb{K}\text{ (genannt "Multiplikation")}$$
für die gelten:
1. $\mathbb{K}$ ist bezgl. $+$ eine kommutative Gruppe, d.h.
	1. $x,y\in\mathbb{K}$ $x+y=y+x\in\mathbb{K}$
	2. $0\in\mathbb{K}$, sodass $x+0=0+x=x$ (*neutrales Element* bezgl. $+$)
	3. es gibt ein *inverses Element* $x'=:(-x)$, sodass $x+x'=x+(-x)=0$
	4. *Assoziativgesetz* $x+(y+z)=(x+y)+z$
2. $\mathbb{K}$ ist bezgl. $\cdot$ eine kommutative Gruppe mit neutralem Element $1\in\mathbb{K}$, und Inverse $x'=:(\frac{1}{x})$ $\forall x\in\mathbb{K}\setminus\{0\}$
3. Es gilt $x,y,z\in\mathbb{K}$ $x\cdot(y+z)=x\cdot y+x\cdot z$ (*Distributivgesetz*)
Dann heißt $\mathbb{K}$ ein **Körper**
### Beispiele für Körper
- Die [[reelle Zahlen|reellen Zahlen]]
- $\mathbb{F}_2$:
| +       | 0   | 1   |
| ------- | --- | --- |
| 0       | 0   | 1   |
| 1       | 1   | 0   |

| $\cdot$ | 0   | 1   |
| ------- | --- | --- |
| 0       | 0   | 0   |
| 1       | 0   | 1   |

