---
aliases: [Postsche Korrespondenzproblem, PKP]
tags:
- BuK
---
Das *Postsche Korrespondenzproblem* ist eine Art Puzzle aus Dominos:
- Ein Domino hat immer ein Wort in der oberen und eins in der unteren Hälfte
- Die Aufgabe ist es, eine Folge von Dominos zu ermitteln, sodass oben und unten dasselbe Wort steht
- Wiederholungen von Dominos sind erlaubt
- Nicht für jede Menge an Dominos gibt es eine Lösung


> [!NOTE] 
> Das PKO gehört zu den [[Entscheidbarkeit#Semi-Entscheidbar / Erkennbar|Semi-Entscheidbaren]] Problemen


### Beispiel
#### Menge der Dominos
$$K=\left\{\left[\frac{b}{ca}\right],\left[\frac{a}{ab}\right],\left[\frac{ca}{a}\right],\left[\frac{abc}{c}\right]\right\}$$
#### Mögliche Lösung
$$\left[\frac{a}{ab}\right]\left[\frac{b}{ca}\right]\left[\frac{ca}{a}\right]\left[\frac{a}{ab}\right]\left[\frac{abc}{c}\right]$$

## Modifiziertes PKP
Das *Modifizierte PKP*  ist im Grunde dasselbe wie ein normales PKP, nur dass es einen Startdomino gibt, mit dem die Lösung beginnt.

> [!NOTE]
> MPKP $\leq$ PKP
