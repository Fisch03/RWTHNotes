---
aliases: []
tags:
- BuK
---

Die universelle [[Turing Machine]] ist im Gegensatz zu der "klassischen" TM ein *general purpose* Rechner.

- Die universelle TM $U$ bekommt als Programm die Kodierung einer beliebigen TM $M$.
- $\langle M \rangle$ ist die Kodierung von $M$. Die genutzte Kodierung sind sog. [[Gödelnummern]]
- Die Eingabe von $U$ ist ein String der Form $\langle M \rangle w$, bestehend aus der TM-Kodierung $\langle M \rangle$ und der Wort $w$
- $U$ simuliert nun das Verhalten von $M$ mit dem Eingabewort $w$

![[../res/u-tm.png]]