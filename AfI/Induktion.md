---
tags:
 - AfI
---
Ist ein [[Beweisverfahren]]

# Allgemeines Vorgehen
zu beweisen: $A(n)\forall n\in\mathbb{N}$ (oder $n\in\mathbb{N}_0$)
1. *Verankerung*: zeige, dass $A(1)$ gilt. (oder $n=0,...$)
2. *Induktionsvorraussetzung*: Es gilt $A(n-1)$ (oder $A(n)$)
3. *Induktionsschritt*: $A(n-1)\Rightarrow A(n)$ (oder $A(n)\Rightarrow A(n+1)$)

## Beispiel
### Satz
Betrachte die Summe $1+2+3+...+n=\sum\limits_{k=1}^{n}k$. Für alle $n\in\mathbb{N}$ gilt $\sum\limits_{k=1}^{n}k=\frac{n(n+1)}{z}$
### Beweis (durch Induktion)
#### Induktionsverankerung
$$\sum\limits_{k=1}^{n}k=1=\frac{1(1+1)}{2}$$
#### Induktionsschritt
($n-1$ gegeben, beweise den Fall $n$)
Es gelte also (Induktionsvorraussetzung): $$\sum\limits_{k=1}^{n-1}k=\frac{(n-1)(n-1+1)}{2}=\frac{(n-1)n}{2}$$
Zu zeigen:$$\sum\limits_{k=1}^{n}k=\frac{n(n+1)}{2}$$
Es folgt:$$\sum\limits_{k=1}^{n}k=\sum\limits_{k=1}^{n-1}k+n=\frac{(n-1)n}{2}+n=\frac{n(n+1)}{2}$$
