---
type: concept
domain: modélisation physique
---

# Équation d'onde

## Définition
Équation aux dérivées partielles décrivant la propagation spatiale d'une perturbation oscillante à travers un milieu continu.

Elle formalise le couplage entre la dynamique temporelle et la structure spatiale.

---

## Forme mathématique (Équation de d'Alembert)
$$
\frac{\partial^2 u}{\partial t^2} - c^2 \Delta u = 0
$$

- $u$ : champ de la perturbation (pression, déplacement, champ électrique).
- $t$ : temps.
- $\Delta$ : [[Laplacien]] (opérateur de diffusion/courbure spatiale).
- $c$ : célérité (vitesse de propagation de l'onde).

---

## Sens physique profond
L'équation d'onde exprime une **mémoire spatio-temporelle**. 
Une accélération en un point du milieu ($\partial^2 u / \partial t^2$) est causée par une "tension" ou une courbure du champ en ce même point ($\Delta u$). Le milieu agit comme une collection infinie d'oscillateurs couplés.

---

## Nature de la célérité
La vitesse $c$ dépend des propriétés intrinsèques du milieu :
- raideur : plus le milieu est rigide, plus $c$ augmente.
- inertie : plus le milieu est dense, plus $c$ diminue.

---

## Portée transdisciplinaire
- acoustique : propagation de la pression dans les fosses nasales ([[Humming]]).
- mécanique : transmission des ondes de choc dans les os ([[Conduction osseuse]]).
- optique : propagation des ondes électromagnétiques.

---

## Liens conceptuels
- [[Propagation]]
- [[Vibration acoustique]]
- [[Vibration mécanique]]
- [[Laplacien]]

## Sources
- @