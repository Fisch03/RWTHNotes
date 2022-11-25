---
aliases: [Regulären Ausdruck]
tags:
- FoSAP
---
# Reguläre Ausdrücke
Reguläre Ausdrücke sind ein Möglichkeit [[Sprachen]] zu beschreiben
- *deklarativ* ("direkt")
- Mithilfe von [[Sprachen#Operationen auf Sprachen|Mengenoperationen]]

## Beispiele
1. $a(a+b)^{*}bb$: Alle Wörter die mit einem $a$ beginnen und mit zwei $b$ enden

## Syntax
### Vereinfachungen
- Weglassen des Punktes $\cdot$
- Weglassen von Klammern falls überflüssig
- Statt $S={a_{1},...,a_k}$ : $\sum\limits_{a \in S}$ oder $\sum\limits_{i=1}^{k}$ 

## Sprachen aus Regulären Audrücken
$L(r)$: Sprache die aus dem regulären Ausdruck $r\in RA_\Sigma$   

## Reguläre Audrücke in Unix
- $a_{1}a_{2}...a_{n}$ statt $a_{1}+a_{2}+...+a_{n}$
- Punkt "." steht für beliebiges Zeichen
- $|$ statt $+$
- $r?$ statt $\epsilon+r$