---
type: concept
domain: mathématiques / mécanique
---

# Jacobien

## Définition
Le jacobien est le tenseur d'ordre 2 (matrice) représentant la dérivée d'une fonction vectorielle par rapport à une variable vectorielle. 

C'est l'**opérateur de linéarisation locale** par excellence.

---

## Formalisme
Pour une fonction $\mathbf{F}: \mathbb{R}^n \to \mathbb{R}^m$ :
$$
\mathbf{J}_{\mathbf{F}} = \left[ \frac{\partial F_i}{\partial x_j} \right]
$$
Si $\mathbf{F}$ représente le déplacement d'un milieu continu, $\mathbf{J}_{\mathbf{F}}$ est le **gradient de transformation**.

---

## Sens physique profond : Déformation et Volume
Le jacobien capture comment un petit vecteur $d\mathbf{x}$ est transformé en un vecteur $d\mathbf{F}$ :
1. **Linéarisation** : $\mathbf{F}(\mathbf{x} + d\mathbf{x}) \approx \mathbf{F}(\mathbf{x}) + \mathbf{J}_{\mathbf{F}} d\mathbf{x}$.
2. **Déterminant Jacobien ($det(\mathbf{J})$)** : il mesure le changement de volume local lors d'une transformation :
    - $det(\mathbf{J}) > 1$ : expansion (dilatation).
    - $det(\mathbf{J}) < 1$ : contraction (compression).
    - $det(\mathbf{J}) = 1$ : conservation du volume (isochore).

---

## Applications en Mécanique
Le jacobien du champ de vitesse d'un fluide se décompose en :
- une partie symétrique : le **taux de déformation** (étirement).
- une partie antisymétrique : le **vorticité** (rotation locale).

---

## Applications au "Locomotion Lab"
- **Anatomie dynamique** : changement de volume des muscles lors de la contraction.
- **Robotique / Contrôle** : le jacobien relie les vitesses articulaires (angles) à la vitesse de l'extrémité du membre dans l'espace.
- **Changement de coordonnées** : passage des coordonnées cartésiennes aux coordonnées cylindriques ou sphériques (ex : pour modéliser un vaisseau sanguin).

## Liens conceptuels
- [[Gradient]]
- [[Tenseur]]
- [[Système]]

## Sources
- @