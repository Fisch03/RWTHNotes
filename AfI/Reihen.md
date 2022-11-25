---
aliases: [Reihe]
tags:
- AfI
---
Praktisch alle interessanten mathematischen Objekte können durch Reihen dargestellt werden.

## Definition
Sei $(a_{n})\subset\mathbb{R}$ eine [[Folgen|Folge]]. Die zugeordnete *Reihe* ist die Folge der Partialsummen
$s_{n}:=\sum\limits_{k=1}^{n}a_{k}=a_{1}+a_{2}+...+a_{n}$ d.h. $\{s_{n}\}=\{s_1,s_2,s_3,...\}=\{a_{1},a_{1}+a_{2},a_{1}+a_{2}+a_{3},...\}$
und für den Grenzwert schreiben wir $\displaystyle\lim_{n\rightarrow\infty}s_{n}=\lim_{n\rightarrow\infty}\sum\limits_{k=1}^{n}a_{k}=:\sum\limits_{k=1}^{\infty}a_{k}$. 
Oft nennen wir die Reihe einfach $\sum\limits_{k=1}^{\infty}a_{k}$.

## Beispiele
1. Die arithmetische Reihe $\sum\limits_{k=1}^{\infty}k$. Offenbar gilt $s_{n}=\sum\limits_{k=1}^{n}k=\frac{n(n+1)}{2}$
   Die Reihe lautet also $\{s_{n}\}=\left\{\frac{n(n+1)}{2}\right\}\subset\mathbb{R}$. $\displaystyle\lim_{n\rightarrow\infty}s_{n}$ existiert nicht ([[Konvergenz + Divergenz#Bestimmt/Unbestimmt divergent|bestimmt divergent]]).
2.  Die geometrische Reihe $\sum\limits_{k=0}^{\infty}q^{k}$ mit $q\in\mathbb{R}$. 
   Für die Partialsummen gilt $s_{n}=\sum\limits_{k=0}^{n}q^{k}=\frac{1-q^{n+1}}{1-q}$
   Die Folge $\{s_{n}\}_{n\in\mathbb{N}}$ [[Konvergenz + Divergenz|konvergiert]], falls $|q|<1$, sonst ist sie [[Konvergenz + Divergenz|divergent]].
3. Die harmonische Reihe $\sum\limits_{k=1}^{\infty}\frac{1}{k}=1+\frac{1}{2}+\frac{1}{3}+\frac{1}{4}+...$ [[Konvergenz + Divergenz|divergiert]] 
4. $\sum\limits_{k=1}^{\infty}\frac{1}{k(k+1)}=\frac{1}{2}+\frac{1}{6}+\frac{1}{12}+\frac{1}{20}+...$ konvergiert gegen $1$ 
5. $\sum\limits_{k=1}^{\infty}\frac{1}{k^2}=1+\frac{1}{4}+\frac{1}{9}+\frac{1}{16}+...$ konvergiert gegen $\frac{\pi^2}{6}$