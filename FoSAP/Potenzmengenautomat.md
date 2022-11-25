---
tags:
- FoSAP
---
# Potenzmengenautomat
Mit dem Potenzmengenautomat lässt sich ein [[NFA]] in einen [[DFA]] umwandeln.

Sei $A=(Q,\Sigma,\Delta,q_0,F)$ ein [[NFA]]

Der Potenzmengenautomat von $A$

#TODO

## Beispiel
![[../res/potenzmengenautomat.png]]
>[!WARNING] Achtung
> Die Zustände $\{\varnothing\}$, $\{q_{1}\}$, $\{q_{2}\}$, $\{q_{1},q_{2}\}$ und $\{q_{0},q_{2}\}$  sind unerreichbar

## Reduzierter PMA
Bei der Konstruktion eines Potenzmengenautomates kann man bereits die unerreichbaren  Zustände ausschließen. Dies nennt sich *Reduktion*