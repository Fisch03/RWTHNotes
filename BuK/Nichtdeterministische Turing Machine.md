---
aliases: [NTM]
tags:
- BuK
---
Eine *Nichtdeterministische Turing-Machine* ist ähnlich wie eine "normale" [[Turing Machine]], nur dass die Zustandübergangsfuntion zu einer Relation wird. Sie nutzt also einen [[../FoSAP/NFA|NFA]] für ihre Übergänge

Sie akzeptiert eine Eingabe $x\in\Sigma^*$ solange es mindestens einen Rechenwg gibt der in den akzeptierenden Zustand führt 

Die Laufzeit von einer NTM $M$ auf einer Eingabe $x\in L(M)$ ist definiert als 
$T_M(x):=$ Länge des kürzesten akzeptierenden Rechenweges von $M$ auf $x$

![[res/ntm.png]]


## Berechnungsbaum
![[/res/ntm_tree.png]]