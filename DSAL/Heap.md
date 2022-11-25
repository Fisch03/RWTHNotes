---
tags:
- DSAL
---
# Heap
[[Bäume|Binärbaum]], nur dass die Sortierung der Knoten nicht mehr nach einem Schlüssel erfolgt, sondern anhand der Priorität der Knoten. Der wichtigste/am meisten gebrauchte Knoten wird als Wurzel gespeichert, danach absteigend

### Einfügen von Elementen
1. Element wird ganz unten eingefügt
2. Priorität wird mit der des darüberliegenden vergleicht
3. Falls größer werden die beiden getauscht
4. Tausch wiederholen bis Parent nicht mehr größer

### Entfernen von Elementen
1. Wurzel wird gelöscht
2. Hinterster Knoten (des Arrays) wird zur neuen Wurzel
3. Mit darunterliegenden vergleichen und ggf. tauschen
4. Wiederholen bis kein Tausch mehr nötig