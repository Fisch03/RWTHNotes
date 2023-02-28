---
aliases: []
tags:
- AfI
---

$$\int\frac{y^4+2y^2+1}{y^4-y^2}dy=\int\left(1+\frac{3y^2+1}{y^4-y^2}\right)dy=y+\int\underbrace{\frac{3y^2+1}{y^4-y^2}}_{???}dy$$
Idee: schreibe eine rationale Funktion $\frac{P(x)}{Q(x)}$ mit $P,Q$ Polynomen in $x$, $grad(P)\subset grad(q)$ als Summe von einfachen Brüchen deren nenner Teiler von $Q(x)$ sind.

### Beispiel 1
$$\frac{1}{y^{4}-y^{2}}=\frac{1}{y^{2}\underbrace{(y-1)(y+1)}_{y^{2}-1}}\overset{?}{=}\underbrace{\frac{A}{y^{2}}\frac{B}{y-1}\frac{C}{y+1}}_{\text{Ansatz}}\quad A,B,C\leq{?}$$
Es gilt (Hauptnenner): $$\frac{1}{\cancel{y^{2}(y-1)(y+1)}}=\frac{A(y-1)(y+1)+By^{2}(y+1)+Cy^{2}(y-1)}{\cancel{y^{2}(y-1)(y+1)}}\quad \forall y\in\mathbb{R}\setminus\{0,\pm1\}$$
Koeffizientenvergleich:
$$1=\underbrace{(B+C)}_{=0}y^{3}+\underbrace{(A+B-C)}_{=0}y^{2}-\underbrace{A}_{-1}\quad\forall y\in\mathbb{R}\setminus\{0,\pm1\}$$
$\Rightarrow$ Gleichungssystem
$$
\begin{align*}
B+C&=0\\
A+B+C&=0\\
A&=-1
\end{align*}\Rightarrow A=-1, B=\frac{1}{2}, C=-\frac{1}{2}\quad\frac{1}{y^{4}-y^{2}}=\frac{-1}{y^{2}}+\frac{\frac{1}{2}}{y-1}+\frac{-\frac{1}{2}}{y+1}
$$