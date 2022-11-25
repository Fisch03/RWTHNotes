---
aliases: [Baum, Binärbaum]
tags:
- Progra
- DSAL
- DS
---
# Bäume
- Ein Baum $B=(V,E)$  besteht aus einer Menge von Knoten $V$ und einer Menge von Kanten $E$
- Knoten: $V=\{v_1,...,v_n\}$
- Kanten: $E=\{(a_1,b_1),...,(a_m,b_m)\}$

Binärbaum: Jeder Knoten hat maximal zwei Nachfolger
Quadtree: vier Nachfolger

## Begriffe
| Begriff        | Erklärung                             |
| -------------- | ------------------------------------- |
| Pfad           | Folge von Kanten                      |
| Tiefe          | Länge eines Pfades von der Wurzel aus |
| Höhe           | Tiefe des untersten Knoten            |
| Grad           | Anzahl der Knoten eines Nachfolgers   |
| Blätter        | Knoten ohne Nachfolger                |
| innerer Knoten | Knoten mit Nachfolger                 | 

- *Balancierter* Baum: Unterschied zwischen tiefsten und höchstem Knoten ist maximal 1
- *Vollständiger* Baum: Jeder Knoten "ausgefüllt"

## Maximale/Minimale Höhe/Knoten
| Szenario           | $H_{max}$ | $H_{min}$                               | $N_{max}$   | $N_{min}$      |
| ------------------ | --------- | --------------------------------------- | ----------- | -------------- |
| Binärbaum generell | $n-1$     | $\lceil log_{2}(n+1)\rceil-1$           |             |                |
| Balancierter Baum  |           | ca. $2\cdot\lceil log_{2}(n+1)\rceil-1$ | $2^{h+1}-1$ | $\sqrt{2^{h}}$ |

## Löschung von Knoten
### Blatt-Knoten
kann einfach entfernt werden

### nur einen Nachfolger
Teilbaum unter dem gelöschten Knoten wird nach oben gerückt

### zwei Nachfolger
Löschung nicht leicht möglich, daher:
- Entfernung eines anderen Knotens (der nächthöhere/tiefere)
- Überschreiben des Wertes vom ursprünglichen Knoten mit dem gelöschtengbhbbb

## Speicherung in Arrays
Geht davon aus dass der Baum vollständig ist
![[arraytree.png]]
- Rot: Wurzel
- Orange: Nachfolger der Wurzel
- usw.

## Traversierung
>[!INFO]
>W: Wert des Knotens, L: Zum Linken Knoten, R: zum Rechten Knoten
- WLR: *Präfix*
- LWR: *Infix*
- LRW: *Postfix*

## kD-Bäume
![[kd-baum.png]]
Binärbaum der Daten mit mehreren Schlüsseln darstellt

Im Bild: Immer abwechselnd Unterteilung X/Y, Aufteilung so dass immer gleich viele Elemente auf jeder Seite sind