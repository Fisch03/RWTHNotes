---
aliases: [stetig]
tags:
- AfI
---
## Arten von Stetigkeit
### Stetigkeit
Eine [[Abbildungen|Funktion]] $f:D\subset\mathbb{R}\rightarrow\mathbb{R}$ heißt *stetig* in $x_0\in D$, wenn
$$\forall\varepsilon>0,\exists\delta=\delta(x_0,\varepsilon)\text{ so, dass } |x-x_0|\subseteq\delta\Rightarrow|f(x)-f(x_0)|\subseteq\varepsilon\quad \forall x\in D$$
zu jeder Genauigkeit $\varepsilon$ von $f(x_0)$ findet sich eine erlaubte Abweichung $\delta$ von $x_0$ so, dass die Auswertung $f(x_0)$  $\varepsilon$-genau ist.

> [!NOTE] Stetigkeit zweier Funktionen
> Sind zwei Funktionen $f$ und $g$ stetig bei $x_0$. Dann sind $\alpha f+\beta g$ mit $\alpha,\beta\in\mathbb{R}$, $f\cdot g$ und $frac{f}{g}$ auch stetig bei $x_0$. Desweiteren ist $f\circ g$ stetig bei $x_0$ falls $f$ stetig bei $g(x_0)$ 

#### Bemerkungen
1. Stetigkeit hängt vom Auswertungspunkt $x_{0}\in D$ ab.
2. Das $\delta$ hängt von $\varepsilon$ und $x_{0}$ ab.

### Gleichmäßige Stetigkeit
$f$ heißt *gleichmäßig stetig*, falls für alle $x\in D$ gilt
$$\forall\varepsilon>0,\exists\delta=\delta(\varepsilon)\text{ so, dass } |x-y|\subseteq\delta\Rightarrow|f(x)-f(y)|\subseteq\varepsilon\quad \forall x\in D$$

### Lipschitz-Stetigkeit
$f$ heißt *Lipschitz-Stetig*, falls $f$ für alle $x,y\in D$
$$\exists L>0 \text{ mit } |f(x)-f(y)|\subseteq L|x-y|$$
$\Rightarrow$ Die Steigung der Funktion ist nirgendswo größer als $L$

### Kontraktion
$f$ heißt *Kontraktion*, falls $f$ Lipschitz-Stetig mit $0<L<1$ ist.
$\Rightarrow$ Die Steigung der Funktion ist nirgendswo größer als $1$


> [!NOTE] 
> "Stetigkeit < Gleichmäßige Stetigkeit < Lipschitz-Stetigkeit < Kontraktion"

## Beispiele

$f(x)=\frac{1}{x}$ ist nicht gleichmäßig stetig, denn die Stetigkeit liefert die erlaubte Abweichung bei $x_0$ als $\delta(\varepsilon, x_0)=x_0\frac{\varepsilon x_0}{\varepsilon x_0+1}$ Für $x_0\in(0,1)$ $\delta=0$

---

$f(x)=\sqrt{x}$ ist stetig, allerdings nicht Lipschitz-Stetig da die Steigung bei 0 gegen $\infty$ geht.