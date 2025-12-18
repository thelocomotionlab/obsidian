---
type: concept 
domain: math
---

# Hessien

## Définition
Pour un [[Champ scalaire]] $\phi:\mathbb{R}^n\to\mathbb{R}$,
le **hessien** est la matrice des dérivées secondes :
$$
H_\phi(\mathbf{x})=\left[\frac{\partial^2\phi}{\partial x_i\partial x_j}\right]_{i,j=1..n}
$$

## Sens fondamental
Il encode la **courbure locale** de $\phi$.
Approximation quadratique :
$$
\phi(\mathbf{x}+\delta\mathbf{x})\approx \phi(\mathbf{x})+\nabla\phi(\mathbf{x})\cdot\delta\mathbf{x}
+\frac12\,\delta\mathbf{x}^\top H_\phi(\mathbf{x})\,\delta\mathbf{x}
$$

## Objets liés
- [[Gradient]] puis dérivation : $H_\phi=\nabla(\nabla\phi)$ (selon convention)
- [[Champ tensoriel]] : $H_\phi$ est un tenseur d’ordre 2
- [[Laplacien]] : $\Delta\phi = \mathrm{tr}(H_\phi)$ (trace)

## Exemples universels
- Quadratique $\phi(\mathbf{x})=\mathbf{x}^\top A\mathbf{x}$ (matrice symétrique $A$) :
$$
H_\phi = 2A
$$
- Optimisation : signe des valeurs propres de $H_\phi$ → min/max/selle (avec hypothèses standard de régularité).
