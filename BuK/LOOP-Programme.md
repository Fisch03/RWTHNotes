---
aliases: [LOOP]
tags:
- BuK
---
## Eigenschaften
Alle LOOP-Programme halten bei jeder Eingabe an, sie berechnen also immer totale Funtionen. Die durch LOOP-Programme berechenbare Funktionen heißen *LOOP-Berechenbar*.

LOOP-berecehnbare Funktionen entsprechen genau den
*primitiv rekursiven Funktionen*. Das sind Funktionen, deren Wert an der  
Stelle n rekursiv aus den Werten an Stellen $k<n$ definiert wird.

## Elemente eines LOOP-Programms
- Variablen $x_0,x_1,...$
- Konstanten $1,0,-1$
- Symbole $:=$ $+$ $;$ $\neq$
- Schlüsselwörter $\texttt{LOOP DO END}$

### Hintereinanderausführung
Zwei Programme $P_1$ und $P_2$ lassen sich auch hintereinander ausführen:
$$P_1;P_2$$
### Loop-Konstrukt
Ist $P$ ein Programm so ist auch 
$$\texttt{LOOP }x_{1}\texttt{ DO } P \texttt{ END}$$

## Beispielprogramme
#### Addition
$$\begin{align*}
&x_0:=x_{1+0}\\
&\texttt{LOOP }x_{2}\texttt{ DO } x_0:=x_0+1 \texttt{ END}
\end{align*}$$
#### Multiplikation
$$\begin{align*}
&\texttt{LOOP }x_{1}\texttt{ DO}\\
&&\texttt{LOOP }x_{2}\texttt{ DO } x_0:=x_0+1 \texttt{ END}\\
&\texttt{END}
\end{align*}$$