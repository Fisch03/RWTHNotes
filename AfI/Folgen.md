---
aliases: [Folge]
tags:
- AfI
---
## Definition
Eine [[Abbildungen|Abbildung]] $a:\mathbb{N}\rightarrow\mathbb{A},n\mapsto a(n)$ mit einer bestimmten Menge $A$ (z.B. $\mathbb{R}$ oder $\mathbb{C}$) heißt *Folge*. Statt $a(n)$ schreiben wir $a_{n}$ und statt $a$ oft $(a_{n})_{n\in\mathbb{N}}$ oder $\{a_{n}\}_{n\in\mathbb{N}}\subset A$. - - 

- Die $a_n$ werden als *Folgenglieder* bezeichnet
- Folgen können [[Konvergenz + Divergenz|konvergieren/divergieren]]
- Folgen können auch [[Schranken|beschränkt]] sein

> [!NOTE] 
> Ist eine Folge [[Konvergenz + Divergenz|konvergent]], ist sie auch [[Schranken|beschränkt]]. **Aber nicht andersrum!**

### Wachstum
Eine reelle Folge $(a_{n})\subset\mathbb{R}$ heißt *monoton wachsend*, falls $a_{n}\leq a_{n+1}$ $\forall n\in\mathbb{N}$
Sie heißt *streng monoton fallend* wenn $a_{n}<a_{n+1}$
Dasselbe gilt analog für *(streng) monoton fallend*e Folgen.

Ist $(a_{n})\subset\mathbb{R}$ eine monoton wachsende Folge und [[Schranken|beschränkt]], so ist sie automatisch [[Konvergenz + Divergenz|konvergent]].

## Beispiele
1. $a_n:=\frac{1}{n^2}$ also $1,\frac{1}{4},\frac{1}{8},\frac{1}{16},...$
2. $a_{n}:=1$ also $1,1,1,1,...$
3. $(a_{n})_{n\geq0}$ mit $a_{n}:=2^{n}$ also $1,2,4,8,16,...$
4. $a_{n}:=\textbf{i}^{n}$ also $n=1,a_{n}=\textbf{i},a_{2}=-1,a_3=-\textbf{i},a_4=1,...$

## Rechnen mit Folgen
Seien $(a_{n})$ und $(b_{n})$ [[Konvergenz + Divergenz|konvergente]] [[Folgen]] mit Grenzwerten $a\in\mathbb{R}$ und $b\in\mathbb{R}$ .
Dann gilt:
1. $\displaystyle\lim_{n\rightarrow\infty}(\alpha a_{n}+\beta b_{n})=\alpha a + \beta b$  
2. $\displaystyle\lim_{n\rightarrow\infty}(a_{n}\cdot b_{n})=a\cdot b$
3. $\displaystyle\lim_{n\rightarrow\infty}\left(\frac{1}{a_{n}}\right)=\frac{1}{a}$  und  $\displaystyle\lim_{n\rightarrow\infty}\sqrt{a_{n}}=\sqrt{a}$
