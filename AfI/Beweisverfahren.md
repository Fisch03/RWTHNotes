---
aliases: []
tags:
- AfI
---
# Direkter Beweis
Beim direkten Beweis wird aus den Vorraussetzungen $A$ die Aussage $B$ direkt hergeleitet: ("$A\Rightarrow B$")

### Satz
$$\forall n\in\mathbb{N}: \sum\limits_{k=1}^{n}k=\frac{n(n+1)}{2}$$
### Beweis
$$S_n=\sum\limits_{k=1}^{n}k$$
$$
\begin{aligned}
	2S_n=&1+2+3+...+(n-1)+n\\
	+&n+(n-1)+...+3+2+1\\
	=&(n+1)+(n+1)+(n+1)+...+(n+1)+(n+1)=n(n+1)
\end{aligned}$$

# Indirekter Beweis
Beweis durch Widerspruch, d.h. wir nehmen das Gegenteil der Aussage $A$ an und leiten etwas offensichtlich falsches ab, dann muss die Aussage $\neg A$ falsch geweisen sein. ("$\neg B \Rightarrow \neg A$")

### Satz
Es gibt unendlich viele Primzahlen

### Beweis
Annahme: Es gibt endlich viele Primzahlen, $p_n$ ist die höchte Primzahl $p_1,p_2,p_3,...,p_n$ Primzahlen, neue Zahl $p_1,p_2,p_3,...,p_{n}+1=q$
$q$ ist nicht teilbar durch $p_1,...,p_n$ (Rest $1$), also entweder ist $q$ prim oder es existiert eine weitere Primzahl $p_{n+1}$