---
type: concept
domain: math
---

# Jacobien

## Définition
Pour un [[Champ vectoriel]] $\mathbf{F}:\mathbb{R}^n\to\mathbb{R}^m$,
le **jacobien** est la matrice :
$$
J_{\mathbf{F}}(\mathbf{x})=\left[\frac{\partial F_i}{\partial x_j}\right]_{i=1..m,\ j=1..n}
$$
Quand $m=n$, c’est un champ tensoriel d’ordre 2 (matrice carrée).

## Sens fondamental
C’est la **meilleure approximation linéaire locale** :
$$
\mathbf{F}(\mathbf{x}+\delta\mathbf{x})\approx \mathbf{F}(\mathbf{x}) + J_{\mathbf{F}}(\mathbf{x})\,\delta\mathbf{x}
$$

## Objets liés
- [[Gradient]] : cas particulier $m=1$ (jacobien = gradient transposé selon convention)
- [[Champ tensoriel]] : $J_{\mathbf{F}}$ est un tenseur d’ordre 2
- En mécanique : $\nabla\mathbf{v}$ (gradient de vitesse) → taux de déformation, rotation, etc.

## Exemple universel
Si $\mathbf{F}(x,y)=(x^2y,\ \sin x)$,
$$
J_{\mathbf{F}}=
\begin{pmatrix}
\partial_x(x^2y) & \partial_y(x^2y)\\
\partial_x(\sin x) & \partial_y(\sin x)
\end{pmatrix}
=
\begin{pmatrix}
2xy & x^2\\
\cos x & 0
\end{pmatrix}
$$
