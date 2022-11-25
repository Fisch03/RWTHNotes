---
aliases: [Nichtdeterministischer endlicher Automat]
tags:
- FoSAP
---
# Nichtdeterministischer endlicher Automat (NFA)
$A=(Q,\Sigma,\Delta,q_0,F)$

| Zeichen  | Erklärung                                            |
| -------- | ---------------------------------------------------- |
| $Q$      | Menge der *Zustände*                                 |
| $\Sigma$ | [Eingabealphabet](Alphabet.md)                          |
| $\Delta$ | *Transitionsfunktion* (Abbildung der "Verbindungen") |
| $q_0$    | *Anfangszustand*                                     |
| F        | Menge der *Endzustände*                              |
DFAbb
- Basierend auf dem [[DFA|DFA]]
- Es kann mehrere Übergänge für aus einem Zustand geben, die dasselbe Zeichen haben
- Gibt es mehrere Möglichkeiten, "zweigt" sich die Ausführung ab
- Es genügt ein erfolgreicher Lauf damit der Automat das Wort akzeptiert

## Beispiel
![[nfa.png]]