---
aliases: [beschränkt]
tags:
- AfI
---

## Schranken von Mengen
Eine Teilmenge $A\subseteq\mathbb{R}$ heißt *von oben beschränkt*, falls ein $b\in\mathbb{R}$ existiert, mit $a\leq b$ $\forall a\in A$. $b$ heißt eine *obere Schranke*.
Desweiteren heißt $s\in\mathbb{R}$ *kleinste obere Schranke* für $A$ falls $S$ eine obere Schranke ist und für jede obere Schranke $b\in\mathbb{R}$ von $A$ gilt $s\leq b$ 
Analog für *von unten beschränkt* und die *größte untere Schranke*

## Schranken von Folgen
$(a_{n})\subset\mathbb{R}$ heisst *beschränkt*, falls es ein $S\in\mathbb{R}, S\geq0$ gibt mit $|a_{n}|\subseteq S$  $\forall n\in\mathbb{N}$

## Supremum und Infimum
Wir benutzen das Supremum für die kleinste obere Schranke 
$$sup A:=min\{b\in\mathbb{R}|a\leq b\forall a\in A\}$$
Wir benutzen das Infimum für die größte untere Schranke
$$inf A:=max\{b\in\mathbb{R}|a\geq b\forall a\in A\}$$

> [!NOTE] 
> Falls $sup A\in A$ ist das Supremum das Maximum $max A$ und fall $inf A \in A$ ist das Infimum das Minimum $min A$ 

#### Beispiel
- $A=(0,1)=\{x\in\mathbb{R}|0<x<1\}$  $max A=?$  $sup A=1$
- $A=[0,1]$  $sup A=max A=1$
- $A=\{a\in\mathbb{R}|a^{2}\leq2\}\subseteq\mathbb{R}$  $sup A \in\mathbb{R}$ nach [[Vollständigkeitsaxiom]] ($sup A=\sqrt{2}$ [[Dichte]])