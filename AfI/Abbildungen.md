---
aliases: [Abbildung, Funktion]
tags:
  - AfI
---

## Definition
Eine *Abbildung $f$ von $M$ nach $N$* ordnet jedem Element $x\in A$ genau ein Element $y\in B$ zu. Man nennt $x$ das *Argument* und $f(x):= y$ das *Bild von $x$ unter $f$* und schreibt dann die Abbildung in der Form

$f:A\to B, x\mapsto f(x)$. 

zum Beispiel:
- $f:\mathbb{R}\to\mathbb{R},x\mapsto x^2$ ist eine Abbildung ($f(x) = x^2$)
- $g:\mathbb{R}\to\mathbb{R},x\mapsto \sqrt{x}$ ist keine Abbildung da für $x<0$ keine Werte zugeordnet werden können
- Solange $A$ eine nicht-leere Menge ist, ist $id_A:A\to A,x\mapsto x$ eine Abbildung. Dies bezeichnet man als die *identische Abbildung auf $A$*
- 
## Bereiche

- $A$ ist der *Definitionsbereich* und $B$ der *Bildbereich* der Abbildung.
- $W_f:=\{y\in B | \exists x\in A \text{ mit } f(x)=y\} =: Im(f)$  ist der *Wertebereich* der Abbildung ("Image")
- $G_f:=\lbrace(x,f(x))|x\in A\rbrace$ ist der *Graph* der Abbildung
![[abb_bereiche.png]]

## Bild/Urbild
- für $f:A\to B$ und $M\subset A$ heißt die Menge $f(M):= \{y\in B | \exists x\in M \text{ mit } f(x)=y\}$ das *Bild* von $M$
- für $N\subset B$ heißt die Menge $f^{-1}(N):=\{x\in A | f(x)\in N\}$ das *Urbild* von $N$
>[!DANGER] Nicht dasselbe wie die Umkehrfunktion! 

## Spezielle Abbildungen
### Identität
Die Identität bildet jeden Wert auf sich selber ab: $f: A\to A, x\mapsto y = f(x) = x$

### konstante Funktion
Die konstante Funktion bildet jeden Wert auf eine Konstante ab: für $c\in B$ definieren wir $f: A\to B, x\mapsto y=f(x)=c$

## Spezielle Eigenschaften
![[abbildung-prop.png]]
### Injektion
$f$ heißt *injektiv*, wenn für alle $a_1,a_2\in A$ aus $f(a_1)=f(a_2)$ stets $a_1=a_2$ folgt, d.h. jedes $y$ besitzt maximal ein $x$ 

### Surjektion
$f$ heißt *surjektiv*, wenn zu jedem $y\in B$ mindestens ein $x\in A$ existiert

### Bijektion
$f$ heißt *bijektiv*, wenn $f$ injektiv und surjektiv ist.

