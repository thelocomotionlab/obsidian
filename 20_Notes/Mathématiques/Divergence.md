---
type: concept
domain: mathématiques / physique
---

# Divergence

## Définition
La divergence est un opérateur différentiel qui mesure la "fuite" ou l'accumulation d'un flux en un point donné. Mathématiquement, elle réduit l'ordre du tenseur : elle transforme un champ vectoriel en un champ scalaire.

---

## 1. Divergence d'un vecteur (Ordre 1 → 0)
Pour un [[Champ vectoriel]] $\mathbf{F}$, la divergence est la somme des dérivées partielles de ses composantes :
$$
\nabla \cdot \mathbf{F} = \text{div}(\mathbf{F}) = \sum_{i=1}^{n} \frac{\partial F_i}{\partial x_i}
$$

---

## 2. Divergence d'un tenseur (Ordre 2 → 1)
Pour un [[Champ tensoriel]] d'ordre 2 (ex : tenseur des contraintes $\boldsymbol{\sigma}$), la divergence produit un vecteur :
$$
(\nabla \cdot \boldsymbol{\sigma})_i = \sum_j \frac{\partial \sigma_{ij}}{\partial x_j}
$$
**Sens physique :** C'est l'outil central pour exprimer les bilans de forces internes dans un matériau ou un tissu biologique.

---

## Sens physique profond : Source ou Puits
La divergence mesure la **création nette de flux** par unité de volume :
- $\nabla \cdot \mathbf{F} > 0$ : le point agit comme une **source** (le flux "naît" ici).
- $\nabla \cdot \mathbf{F} < 0$ : le point agit comme un **puits** (le flux "disparaît" ou s'accumule ici).
- $\nabla \cdot \mathbf{F} = 0$ : le champ est dit **solénoïdal** ou incompressible (ce qui entre égale ce qui sort).

---

## Lien Global ↔ Local (Théorème de Green-Ostrogradski)
Le flux total à travers une surface fermée $S$ est égal à l'intégrale de la divergence dans le volume $V$ qu'elle délimite :
$$
\oiint_S \mathbf{F} \cdot d\mathbf{S} = \iiint_V (\nabla \cdot \mathbf{F}) \, dV
$$

---

## Applications au "Locomotion Lab"
- **Hémodynamique** : l'incompressibilité du [[Sang]] impose $\nabla \cdot \mathbf{v} = 0$.
- **Métabolisme** : l'équation de continuité $\frac{\partial \rho}{\partial t} + \nabla \cdot \mathbf{J} = \sigma$ utilise la divergence pour suivre la conservation de la masse (ex : [[Oxygène]]).
- **Électrophysiologie** : description des sources de courant extracellulaires dans le tissu nerveux.

## Liens conceptuels
- [[Flux]]
- [[Gradient]]
- [[Laplacien]]
- [[Lois de conservation]]

## Sources
- @