---
type: concept
domain: math
---

# Opérateur nabla (∇)

## Définition
En coordonnées cartésiennes dans \(\mathbb{R}^3\) :
\[
\nabla =
\left(\frac{\partial}{\partial x},\frac{\partial}{\partial y},\frac{\partial}{\partial z}\right)
\]
C’est un **opérateur différentiel** qui, combiné avec un champ, produit :
- [[Gradient]] : \(\nabla \phi\)
- [[Divergence]] : \(\nabla\cdot \mathbf{F}\)
- [[Rotationnel]] : \(\nabla\times \mathbf{F}\)
- [[Laplacien]] : \(\Delta \phi = \nabla\cdot\nabla\phi\)

## Lecture conceptuelle
\(\nabla\) “mesure” la **variation locale** :
- d’un scalaire : direction + intensité de la plus forte hausse
- d’un vecteur : tendance à **se dilater** (div) et à **tourner** (curl)

## Objets liés
- [[Champ scalaire]]
- [[Champ vectoriel]]
- [[Champ tensoriel]]
- [[Jacobien]] (souvent écrit \(\nabla \mathbf{F}\))
- [[Hessien]] (souvent écrit \(\nabla^2\phi\))

## Remarque dimensionnelle
En dimension \(n\), \(\nabla=(\partial_{x_1},\dots,\partial_{x_n})\).
Le rotationnel “vectoriel” n’existe au sens simple qu’en 3D (et une version spéciale en 2D). En dimension générale, on généralise via formes différentielles (extérieur \(d\)).
