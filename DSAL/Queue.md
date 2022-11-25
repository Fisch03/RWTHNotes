---
aliases: [Warteschlange]
tags:
- DSAL
---
# Queue
- Eingeschränktere [[List|Liste]]
- Entfernen nur am Anfang, Einfügen nur am Ende möglich
- FIFO

| Operation | Erklärung                         |
| --------- | --------------------------------- |
| Empty()   |                                   |
| Get()     | Gibt das Element am Anfang zurück | 
| Deq()     | Element am Anfang wird entfernt   |
| Enq()     | Element wird am Ende eingefügt    |

## Array-Implementierung
- Keine Garbage-Collection benötigt
- Allerdings: maximale Länge

![[../res/queuearray.png]]
