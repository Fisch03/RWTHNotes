---
tags:
- Progra
- DSAL
- DS
---
# Datentypen
| Bestehen aus              | Beispiel: Uhrzeit                          |
| ------------------------- | ------------------------------------------ |
| Datenobjekte, Datenfelder | hh:mm:ss                                   |
| Funktionen                | Add: Zeit$\times$Zeit$\rightarrow$Zeit     |
| Axiome                    | Add($[h_1,m_1,s_1]$,$[h_2,m_2,s_2]$) = <br>$[h_1+h_2+(m_1+m_2+(s_1+s_2)/60)/60\%24,$ <br> $(m_1+m_2+(s_1+s_2)/60)\%60,$ <br> $(s_1+s_2))\%60]$ |

## Datentypen-Typen
von einfach zu komplex:
1. $0D$  Aufzählungstypen
	- bool
	-  enum
2. $1D$ Skalare Typen
	- char
	- int
	- float
3. $nD$ Zusammengesetzte Typen 
	- struct
	- class
4. $[1:1]$ Lineare Strukturen
	- [[List]]
	- [[Queue]]
	- [[Stack]]
5. $[1:n]$ [[Bäume]]
6. $[n:m]$ [[Graphen]]