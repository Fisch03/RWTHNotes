---
aliases: [Sprache, Formale Sprache]
tags:
- FoSAP
---
# Sprachen
Eine Formale Sprache (kurz: Sprache) ist die Menge aller Wörter in einem [[Alphabet]]

Eine Sprache ist *regulär* falls es einen [[Reguläre Ausdrücke|Regulären Ausdruck]] gint der sie bildet.
## Operationen auf Sprachen
### Vereinigung, Schnitt, Differenz ($\cap,\cup,\backslash$)
### Verkettung 
"Anhängen"   von Wörtern der zweiten Sprache an die erste
### Assoziativ-/Distributivgesetze
- $a \cdot b \cdot c = abc$ 
- $a^4=aaaa$
- $\{a,b\}^{2}=aa,ab,ba,bb$
### Iteration
Vereinigung aller Potenzen
$\displaystyle L^{*}:=\bigcup_{n\in\mathbb{N}}L^{n}=L^{0} \cup L^{1} \cup L^{2},...$
Auch bekannt als *Kleene-Stern* 