---
type: concept
domain: chimie
---

# Gradient électrochimique

## Définition
Le gradient électrochimique est la force motrice nette qui détermine le flux d'une espèce ionique à travers une membrane. 

Il résulte de la superposition de deux gradients distincts : 
1. Un **gradient de concentration** (chimique).
2. Un **gradient de potentiel électrique**.

---

## Définition mathématique
Pour un ion $i$, le gradient de potentiel électrochimique $\nabla \tilde{\mu}_i$ est la variation spatiale de son potentiel électrochimique :

$$
\tilde{\mu}_i = \mu_i^0 + RT \ln(C_i) + z_i F \psi
$$

Le flux $J_i$ est alors proportionnel à ce gradient (équation de Nernst-Planck) :
$$
J_i = -D_i \left( \nabla C_i + \frac{z_i F C_i}{RT} \nabla \psi \right)
$$

- $C_i$ : concentration de l'ion
- $z_i$ : valence de l'ion
- $\psi$ : potentiel électrique local
- $D_i$ : coefficient de diffusion

---

## Sens physique profond
Il représente la **différence de pression énergétique** entre deux compartiments. 
Un ion peut descendre son gradient de concentration tout en remontant un gradient électrique ; c'est le **bilan énergétique total** qui dicte le sens du flux passif.

---

## Nature dynamique
En biologie, le gradient électrochimique est :
- **Une pile** : stockage d'énergie potentielle (ex: gradient de protons $H^+$).
- **Un signal** : sa dissipation rapide (flux ionique) permet le potentiel d'action.
- **Un moteur** : il permet le transport actif secondaire (symport/antiport).

---

## Portée transdisciplinaire
- **Thermodynamique** : étude des systèmes hors équilibre.
- **Électrochimie** : fonctionnement des batteries et piles à combustible.
- **Neurosciences** : base de l'excitabilité cellulaire.

---

## Liens conceptuels
- [[Gradient]]
- [[Potentiel de membrane]]
- [[Potentiel chimique]]
- [[Flux]]

## Sources
- @