---
aliases: []
tags:
- AfI
---
Wir wollen die [[Abbildungen|Funktion]] $f$ an der Stelle $x_0\in\mathbb{R}$ durch eine lineare Funktion approximieren.
Formel: Approximation $g:\mathbb{R}\rightarrow\mathbb{R}$, Gegeben: $f:\mathbb{R}\rightarrow\mathbb{R}$ und Stelle $x_0\in\mathbb{R}$

### Konstante Approximation
$$g:\mathbb{R}\rightarrow\mathbb{R}, x\mapsto g(x)=f(x_0)=\text{const}$$

### Lineare Approximation
$$g:\mathbb{R}\rightarrow\mathbb{R}, x\mapsto g(x)=f(x_0)+a(x-x_0)=\underbrace{f(x_0)-ax_0}_{\hat{=}n}+ax$$
$a\in\mathbb{R}$ so gewählt, dass $g$ doe Funktion $f$ gut approximiert.
$\vartriangle f=f(x_0+h)-f(x_0)$
$\vartriangle g=g(x_0+h)-g(x_0)=ah$
Es gilt $\vartriangle f(h)=ah+r(h)$
