---
aliases: [Graph]
tags:
- DSAL
- DS
---
# Graphen
| Begriff                 | Erklärung                                                                                   |
| ----------------------- | ------------------------------------------------------------------------------------------- |
| stark Zusammenhängend   | Man kommt "von überall nach überall"                                                        |
| schwach Zusammenhängend | stark Zusammenhängend nur jede Kante ist ungerichtet                                        |
| Vollständig             | jeder Knoten ist mit jedem Verbunden ($m=n\times(n-1)/2$)                                   |
| Isomorph                | Nach Vertauschung (Permutation) gleicht der Graph einem anderen<br>  ![[isomorph.png\|250]] |
## Adjazenzmatrix
![[res/adjacency.png|500]]
Speicherverbrauch: $n^2$ bit

## Adjazenzliste
![[res/adjacencylist.png|500]] 
Speicherverbrauch: $n \times k \times b = n \times k \times log(n)$ bit 

## Planarer Graph
![[res/planargraph.png |500]]  
