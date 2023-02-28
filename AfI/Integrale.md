---
aliases: []
tags:
- AfI
---
Integral einer [[Abbildungen|Funktion]] = "Fläche" unter dem Graph
### Lösungsmöglichkeiten
- [[Partielle Integration]]
- [[Partialbruchzerlegung]]


### Bemerkungen
- Für Potenzreihen $f(x)=\sum\limits_{n=1}^{\infty}a_{n}x^{n}$ die absolut konvergieren, dürfen wir termweise integrieren (im Konvergenzbereich) $\int f(x)dx=\sum\limits_{n=1}^{\infty}a_{n}\int x^{n}dx=\sum\limits_{n=1}^{\infty}\frac{a_{n}}{n+1}x^{n+1}+\mathbb{C}$
- Es gibt viele Integrale, die nicht "elementar" integriert werden können z.B. $\int_{0}^{a}e^{-t^{2}}dt$ per Potenzreihe wird definiert $Erf(a):=\frac{2}{\sqrt{\pi}}\int_{0}^{a}e^{-t^{2}}dt=\frac{2}{\sqrt{\pi}}\sum\limits_{k=0}^{\infty}\frac{(-1)^{k}a^{2k+1}}{(2k+1)k!}$ "Fehlerfunktion"

## Hauptsatz der Differential und Integralrechnung
Sei $f:[a,b]\rightarrow\mathbb{R}$ stetig $x,x_0\in[a,b]$ und $F(x):=\int_{x_0}^{x}f(t)dt$ (Grenze ist Variable)
Dann ist $F$ differenzierbar und es gilt
$$F'(x)=\left(\int_{x_0}^{x}f(t)dt\right)'=f(x)\qquad x\in[a,b]$$
$F$ ist die [[Stammfunktionen]] von $f$

Sei $F:[a,b]\rightarrow\mathbb{R}$ und $F\in C^1([a,b])$ mit $F'(x)=f(x)$ für $x\in[a,b]$
Dann ist
$$\int_{a}^{b}f(x)dx=F(x)\big|_{a}^{b}:=F(b)-F(a)$$

## Rechenregeln für Integrale
Seien $f,g$ integrierbar auf $I=[a,b]$. $\alpha,\beta\in\mathbb{R}$ Dann gilt
1. $\int_{a}^{b}f(x)dx=\int_{a}^{c}f(x)dx+\int_{c}^{b}f(x)dx$
2. $\int_{a}^{b}(\alpha f(x)+\beta g(x))dx=\alpha\int_{a}^{b}f(x)dx+\beta\int_{a}^{b}g(x)dx$
3. $f(x)\leq g(x)$ auf $[a,b]\Rightarrow$ $\int_{a}^{b}f(x)dx\leq\int_{a}^{b}g(x)dx$
4. $|\int_{a}^{b}f(x)dx|\leq\int_{a}^{b}|f(x)|dx\leq|f|_{\infty}(b-a)$ mit $|f|_{\infty}:=\underset{x\in I}{\textbf{max}}|f(x)|$
5. Für $g\geq0$, $m\leq f(x)\leq M$ mit $m,M\in\mathbb{R}$ gilt $m\int_{a}^{b}g(x)dx\leq\int_{a}^{b}f(x)g(x)dx\leq M\int_{a}^{b}g(x)dx$

## Mittelwertsatz
Sei $f:[a,b]\rightarrow\mathbb{R}$ stetig. Dann existiert ein $\xi\in(a,b)$ mit $\int_{1}^{b}f(x)dx=f(\xi)(b-a)$

## Riemann-Integral (Beispiel)
$f(x)=x^2$ auf $[a,b]$  Wähle die Zerlegung $x_{i}=i\frac{b}{n}$ $i=0,...,n$
$f$ ist stetig $\Rightarrow$ Obersumme = Untersummen in Grenzwert feiner Zerlegung ($n\rightarrow\infty$)
$O(f,Z_n)=\sum\limits_{i=n}^{n}f(x_{i})(x_{i}-x_{i-1})=\sum\limits_{i=1}^{n}(i\frac{b}{n})^2\frac{b}{n}=(\frac{b}{n})^{3}\sum\limits_{i=1}^{n}i^{2}=b^{3}\frac{n(n+1)(2n+1)}{6n^3}$(Folge)
$\lim_{n\rightarrow\infty}O(f,Z_{n})=\lim_{n\rightarrow\infty}b^{3}\frac{n(n+1)(2n+1)}{6n^3}=b^3\lim_{n\rightarrow\infty}\frac{n(n+1)(2n+1)}{6n^3}=b^3\frac{1}{3}$


