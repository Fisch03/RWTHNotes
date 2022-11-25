---
aliases: [Linearkombination]
tags:
- LA
---
# Linearkombinationen
Linearkombination vom Vektor $(v_1,...,v_n)$  in $V$ der Form
$\displaystyle v=\sum\limits_{i=1}^{n}a_{i}v_{i}$
mit den Koeffizienten $a_1,...,a_{n}\in K$

### Notation
$\langle v_1,...,v_n\rangle$ ist die Menge aller Linearkombinationen

>[!INFO]+
>- Mehrere Linearkombinationen können den gleichen Vektor darstellen.
>- Linearkombinationen sind Untervektorräume ($\langle v_{1},...,v_{n}\rangle\leq V$)

## Beispiele
- in $\mathbb{Q}^{1\times3}$: $(-1,-4,-1)\in\langle(1,2,1),(1,3,1)\rangle$
  Beweis:
 1. $(-1,-4,-1)=a(1,2,1)+b(1,3,1)=(a+b,2a+3b,a+b)$
 2. $\rightarrow$ Lösung  mit [[Gauß-Verfahren]]
 3. $a=1,b=-2$
- $\langle(1,0,0),(0,1,0),(0,0,1)\rangle=\mathbb{R}^{1\times3}$ (siehe auch [[Erzeugendensystem|EZS]])
- $\langle(1,1),(1,2)\rangle=\mathbb{Q}^{1\times2}$ (siehe auch [[Erzeugendensystem|EZS]])
