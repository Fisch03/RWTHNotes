---
aliases: [Menge]
tags:
  - AfI
---
## Definition
Eine *Menge* ist eine Zusammenfassung von Objekten zu einem Ganzen. Die Objekte nennt man Elemente der Menge. Bei jedem Element einer Menge muss man klar entscheiden können ob es zur Menge gehört oder nicht.

Eine Menge kann auf zwei Wege beschrieben werden:
1. $M = \lbrace x,y,z,...\rbrace$ bedeuted dass $M$ genau aus den angegebenen Elementen $x,y,z,...$ besteht.
2. $M = \lbrace x | x$ hat Eigenschaft $E\rbrace$ bedeuted dass $M$ die Menge aus allen Objekten $x$ ist die die Eigenschaft $E$ haben.

Wenn $x$ ein *Element* von $M$ ist, schreibt man $x \in M$. 
Wenn $x$ *kein Element* von $M$ ist, schreibt man $x \notin M$.

zum Beispiel:
- Die Menge aller kleinen lateinischen Buchstaben ($A = {a,b,c,...,x,y,z}$) besitzt 26 Elemente. Es gilt $l \in A$ aber $L \notin A$
- Die *leere Menge* ist die Menge ohne Elemente und wird mit $\emptyset$ oder mit ${}$ bezeichnet (z.B. $\emptyset = \lbrace \rbrace = \lbrace x|x \neq x \rbrace$)

## Teilmengen
$M\subset N$

Sprich: Jedes Element von $M$ ist auch in $N$. $M$ ist in $N$ *enthalten*

$M\subsetneqq N$

Sprich: Jedes Element von $M$ ist auch in $N$, allerdings sind $M$ und $N$ nicht gleich. $M$ ist eine *echte Teilmenge* von $N$

## Gleiche Mengen
$M=N$

Sprich: M und N sind *gleich*

## Mengen-Algebra:
![[Mengen-Algebra]]

### Mächtigkeit
*Mächtigkeit* bezeichnet die Anzahl der Elemente in einer Menge und wird mit oder $|M|$ notiert.
Einige Mengen sind hingegen [[Abzählbarkeit|Überabzählbar]]
- wenn $M = \lbrace1,2,3\rbrace$ dann ist $|M|:=3$. Die Menge ist *endlich*
- Bei $|M| :=\infty$ ist die Menge *unendlich*
- Für die Menge $\emptyset$ gilt $|\emptyset|:=0$
- Für die Menge $\mathbb{N}$ (siehe [[Natürliche Zahlen]]) gilt $|\mathbb{N}|:=\infty$

## Komplement
Ist $M\subset N$ so heißt $N\backslash M$ das *Komplement von $M$ in $N$*. Man schreibt $M^c$

## Potenzmenge
Die *Potenzmenge* von $M$ ist die Menge aller Teilmengen von $M$: 

Pot$(M)$ $:=\lbrace A|A\subset M\rbrace$

zum Beispiel:
- Pot$(\emptyset) = {\emptyset}$
- Pot$(\lbrace a\rbrace) = \lbrace\emptyset,\lbrace a\rbrace\rbrace$
- Pot$(\lbrace a,b\rbrace) = \lbrace\emptyset,\lbrace a\rbrace,\lbrace b\rbrace,\lbrace a,b\rbrace\rbrace$