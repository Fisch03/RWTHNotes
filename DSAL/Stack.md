---
tags:
- DSAL
---
# Stack
- Eingeschränktere [[List|Liste]]
- Einfügen/Entfernen nur am Anfang möglich
- LIFO

| Operation | Erklärung                         |
| --------- | --------------------------------- |
| Empty()   |                                   |
| Top()     | Gibt das Element am Anfang zurück |
| Push()    | Element am Anfang wird entfernt   |
| Pop()     | Element wird am Anfang eingefügt  |          |                                   |

## Array-Implementierung
- Keine Garbage-Collection benötigt
- Allerdings: maximale Länge

![[res/stackarray.png]]