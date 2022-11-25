---
aliases: [Deterministischer Endlicher Automat]
tags:
- FoSAP
---
# Deterministischer Endlicher Automat (DFA)
  $A=(Q,\Sigma,\delta,q_0,F)$
  
| Zeichen  | Erklärung                                            |
| -------- | ---------------------------------------------------- |
| $Q$      | Menge der *Zustände*                                 |
| $\Sigma$ |  [Eingabealphabet](Alphabet.md)                           |
| $\delta$ | *Transitionsfunktion* (Abbildung der "Verbindungen") |
| $q_0$    | *Anfangszustand*                                     |
| F        | Menge der *Endzustände*                                                     |

- Zwei DFAs lassen sich zu einem [[Produktautomat]] kombinieren
## Beispiel
![[dfa.png]]

## Lauf
"Berechnung" eines DFA mit einem Wort
Bei einem DFA ist ein Lauf immer eindeutig

Die von $A$ *erkannte [[Sprachen|Sprache]]* ist eine Menge von aktzeptierten Worten:
$L(A):=\{w\in\Sigma^*|A$ akzeptiert $w\}$

- Wenn $L$ erkennbar ist ist auch $\overline{L}$ erkennbar