---
type: concept
domain: math
---

# Divergence

## Définition
Pour un [[Champ vectoriel]] $\mathbf{F}=(F_1,\dots,F_n)$,
la **divergence** est le champ scalaire :
$$
\nabla\cdot\mathbf{F}=\sum_{i=1}^{n}\frac{\partial F_i}{\partial x_i}
$$
En 3D :
$$
\nabla\cdot\mathbf{F}=\frac{\partial F_x}{\partial x}+\frac{\partial F_y}{\partial y}+\frac{\partial F_z}{\partial z}
$$

## Sens physique fondamental
La divergence mesure la **création nette de flux** autour d’un point :
- $>0$ : comportement de **source** (ça “sort”)
- $<0$ : comportement de **puits** (ça “entre”)
- $=0$ : **incompressible / conservatif localement** (pas de création nette)

## Lien local ↔ global (idée)
Divergence = **flux sortant par unité de volume** (intuition).
Formellement, elle est liée au théorème de Gauss (divergence theorem), qui relie intégrale de volume et flux sur la frontière.

## Objets liés
- [[Champ vectoriel]] → (divergence) → [[Champ scalaire]]
- [[Gradient]] + divergence → [[Laplacien]] : $\Delta\phi=\nabla\cdot\nabla\phi$
- Divergence d’un [[Champ tensoriel]] (ordre 2 → vectoriel) :
$$
(\nabla\cdot \mathbf{T})_i=\sum_j \partial_j T_{ij}
$$

## Exemples universels
### 1) Incompressibilité (fluides)
Si $\mathbf{v}$ = vitesse d’un fluide, incompressible :
$$
\nabla\cdot \mathbf{v}=0
$$

### 2) Continuité (conservation de masse)
$$
\frac{\partial \rho}{\partial t}+\nabla\cdot(\rho \mathbf{v})=0
$$

### 3) Champ radial (source ponctuelle, hors singularité)
Un champ radial “sortant” a divergence positive (hors origine), ce qui formalise l’idée de source.

## Identités utiles
- Produit scalaire–vecteur :
$$
\nabla\cdot(\phi\mathbf{F})=\nabla\phi\cdot\mathbf{F}+\phi(\nabla\cdot\mathbf{F})
$$
