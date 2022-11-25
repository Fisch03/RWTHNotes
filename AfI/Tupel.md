---
aliases: [Paar, Paare]
tags:
  - AfI
---
## Definition
Ein Tupel ist im Grunde dasselbe wie eine Menge, nur dass die Reihenfolge der Elemente fest ist. Tupel werden mit Klammern $()$ gekennzeichnet. Es gilt dementsprechend $(a,b)\ne (b,a)$

Die einzelnen Elemente eines Tupels werden als *Komponenten* bezeichnet (*erste Komponente*, *zweite Komponente*, usw.)

Zwei Tupel sind genau dann gleich wenn sie dieselbe Länge haben und ihre Komponenten gleich sind:
$(a,b)=(x,y)$ wenn $a=x$ und $b=y$

## Tupel in Mengen
- $\mathbb{R}^2=\left\lbrace\left(\begin{array}{c}a\\b\end{array}\right);a,b\in\mathbb{R}\right\rbrace$ 
ist die Menge aller geordneten Paare reeller Zahlen
- $\mathbb{R}^3=\left\lbrace\left(\begin{array}{c}a\\b\\c\end{array}\right);a,b,c\in\mathbb{R}\right\rbrace$ 
ist die Menge aller geordneten Tripel reeller Zahlen
- Allgemeiner (solange $n \in \mathbb{N}$):
$\mathbb{R}^n=\left\lbrace\left(\begin{array}{c}a_1\\...\\a_n\end{array}\right);a_1,...,a_n\in\mathbb{R}\right\rbrace$ 

## geordnete Paare
Bei einem geordneten Tupel mit zwei Elementen spricht man von einem *geordneten Paar*.

## Kartesisches Produkt
$M\times N:=\lbrace(a,b)|a\in M$ und $b\in N\rbrace$

Das *kartesische Produkt* ist die Menge aller geordneten Paare aus den Elementen von $M$ und $N$

**Wichtig:** $M\times N\neq N\times M$

zum Beispiel:
- $\lbrace0,1\rbrace\times\lbrace2,3\rbrace=\lbrace(0,2),(0,3),(1,2),(1,3)\rbrace$